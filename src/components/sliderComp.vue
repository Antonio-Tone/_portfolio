<template>
    <div>
      <div class="gallery">
        <div class="gallery-container">
          <img class="gallery-item gallery-item-1 " src="https://i.postimg.cc/sXvSnZ7v/Screenshot-2023-10-30-151739.png" data-index="1">
          <img class="gallery-item gallery-item-2" src="https://i.postimg.cc/k5NgFMBL/Screenshot-2023-10-30-151253.png" data-index="2">
          <img class="gallery-item gallery-item-3" src="https://i.postimg.cc/q7FCSvkq/Screenshot-2023-10-30-150857.png" data-index="3">
          <img class="gallery-item gallery-item-4" src="https://i.postimg.cc/Qt65mdvf/Screenshot-2023-10-30-150020.png" data-index="4">
          <img class="gallery-item gallery-item-5" src="https://i.postimg.cc/BbZ7zbhk/Screenshot-2023-10-30-144708.png" data-index="5">
        </div>
        <div class="gallery-controls"></div>
      </div>
      
    </div>
  </template>
  <script>
  export default {
    mounted() {
      const galleryContainer = document.querySelector('.gallery-container');
      const galleryControlsContainer = document.querySelector('.gallery-controls');
      const galleryControls = ["previous", "next"];
      const galleryItems = document.querySelectorAll('.gallery-item');
  
      class Carousel {
        constructor(container, items, controls) {
          this.carouselContainer = container;
          this.carouselControls = controls;
          this.carouselArray = [...items];
        }
  
        updateGallery() {
          this.carouselArray.forEach(el => {
            el.classList.remove("gallery-item-1");
            el.classList.remove("gallery-item-2");
            el.classList.remove("gallery-item-3");
            el.classList.remove("gallery-item-4");
            el.classList.remove("gallery-item-5");
          });
          this.carouselArray.slice(0, 5).forEach((el, i) => {
            el.classList.add(`gallery-item-${i + 1}`);
          });
        }
  
        setCurrentState(duration) {
          if (duration.className == 'gallery-controls-previous') {
            this.carouselArray.unshift(this.carouselArray.pop());
          } else {
            this.carouselArray.push(this.carouselArray.shift());
          }
          this.updateGallery();
        }
  
        setControls() {
          this.carouselControls.forEach(control => {
            galleryControlsContainer.appendChild(document.createElement('button')).className = `gallery-controls-${control}`;
            document.querySelector(`.gallery-controls-${control}`).innerText = control;
          });
        }
  
        useControls() {
          const triggers = [...galleryControlsContainer.childNodes];
          triggers.forEach(control => {
            control.addEventListener('click', e => {
              e.preventDefault();
              this.setCurrentState(control);
            });
          });
        }
      }
  
      const prodCarousel = new Carousel(galleryContainer, galleryItems, galleryControls);
      prodCarousel.setControls();
      prodCarousel.useControls();
    }
  }
  </script> 
  <style scoped>
  .card {
  /* width: 600px;
  height: 285px; */
  background: #313131;
  border-radius: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: white;
  transition: 0.2s ease-in-out;
  }
  .links {
  height: 30px;
  }
  .linkBg {
  background-color: transparent !important;
  }
  .textBox {
  opacity: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 15px;
  transition: 0.2s ease-in-out;
  z-index: 2;
  }
  
  .textBox > .text {
  font-weight: bold;
  }
  
  .textBox > .head {
  font-size: 20px;
  }
  
  .textBox > .price {
  font-size: 17px;
  }
  
  .textBox > span {
  font-size: 12px;
  color: lightgrey;
  }
  
  .card:hover > .textBox {
  opacity: 1;
  }
  
  .card:hover > .img {
  filter: blur(7px);
  }
  .card:hover {
  animation: anim 3s infinite !important;
  }
  
  @keyframes anim {
  0% {
    transform: translateY(0);
  }
  
  50% {
    transform: translateY(-20px);
  }
  
  100% {
    transform: translateY(0);
  }
  }
  
  /* testing animation */
  
  
    body{
      margin: 0;
      padding: 0;
      width: 100%;
      display: flex;
      align-items: center;
    }
    .gallery{
      width: 100%;
    }
    .gallery-container{
      align-items: center;
      display: flex;
      height: 400px;
      margin:0 auto;
      max-width: 1000px;
      position: relative;
    }
    .gallery-item{
     height: 210px;
     opacity: 0;
     position: absolute;
     transition: all 0.3s ease-in-out;
     width: 500px;
     z-index: 0;
     border-radius: 15px;
     background-size: contain;
    }
    .gallery-item-1{
      left:8%;
      opacity: .4 ;
      transform: translateX(-50%);
    }
    .gallery-item-2, .gallery-item-4{
      height: 235px;
      opacity: 0.8;
      width: 400px;
      z-index:1 ;
    }
    .gallery-item-2{
  left:23%;
  transform: translateX(-50%);
    }
    .gallery-item-3{
    box-shadow: -2px 5px 33px 6px rgba(0,0,0.35);
    height: 300px;
    opacity: 1;
    left:50%;
    transform: translateX(-50%);
    width:430px;
    z-index: 2;
    }
    .gallery-item-4{
  left: 80%;
   transform: translateX(-50%);
    }
    .gallery-item-5{
      left: 92%;
      opacity: .4;
      transform: translateX(-50%);
  
    }
    .gallery-controls{
      display: flex;
      justify-content: center;
      margin:25px 0 ;
      height: 100px;
    }
    .gallery-controls button{
      background-color: transparent;
      border: 0;
      cursor: pointer !important;
      font-size: 30px;
      margin: 0 50px;
      padding: 0 12px;
      text-transform: capitalize;
    }
    .gallery-controls-button:focus{
      outline: none;
    }
    .gallery-controls-previous{
      position: relative;
    }
 
    .gallery-controls-previous:hover::before{
      left:-40px;
  
    }
    .gallery-controls-next{
      position: relative;
    }
    .gallery-controls-next::before{
      border: solid black;
      border-width: 0 5px 5px 0;
      content: "";
      display: inline-block;
      height: 5px;
      padding: 10px;
      position: absolute;
      right:-30px;
      top:45;
      transform: rotate(-45deg) translateY(-50%);
      transition: right 0.15s ease-in-out;
      width: 5px;
    }
  
    .gallery-controls-next:hover::before{
      right:-40px;
    }
    .galelry-nav{
      bottom: -15px;
      display: flex;
      justify-content: center;
      list-style: none;
      padding: 0;
      position: absolute;
      width: 100%;
    }
  
    .gallery-nav li{
      background-color: white;
      border-radius: 50%;
      height: 10px;
      margin: 0 16px;
      width: 10px;
    }
    .gallery-nav li .gallery-item-selected{
      background-color: grey; 
    }
  
    
     
  </style>