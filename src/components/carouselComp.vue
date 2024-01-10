<template>
    <div>
      <div class="gallery">
        <div class="gallery-container">
          <div class="card">
            <img class="gallery-item gallery-item-1 img" src="https://i.postimg.cc/sXvSnZ7v/Screenshot-2023-10-30-151739.png" data-index="1">
              <div class="textBox" v-show="isHidden">
                <div class="d-flex justify-content-center">
                  <a href="https://lighthearted-marshmallow-2d6528.netlify.app"
                  taget="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif"
                        alt=""
                      /></button
                  ></a>
                  <a href="https://github.com/Antonio-Tone/Profile"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.postimg.cc/d1SJQh7P/output-onlinegiftools-1.gif"
                        alt=""
                      /></button
                  ></a>
                </div>
              </div>
            </div>
          <img class="gallery-item gallery-item-2" src="https://i.postimg.cc/k5NgFMBL/Screenshot-2023-10-30-151253.png" data-index="2">
          <img class="gallery-item gallery-item-3" src="https://i.postimg.cc/q7FCSvkq/Screenshot-2023-10-30-150857.png" data-index="3">
          <img class="gallery-item gallery-item-4" src="https://i.postimg.cc/Qt65mdvf/Screenshot-2023-10-30-150020.png" data-index="4">
          <img class="gallery-item gallery-item-5" src="https://i.postimg.cc/BbZ7zbhk/Screenshot-2023-10-30-144708.png" data-index="5">
        </div>
        <span class="gallery-controls">
          <button class="previous"><img class="ctrl" src="https://i.postimg.cc/zXcxLj4y/icons8-double-left-96.png " alt=""></button>
          <button class="next"><img class="ctrl" src="https://i.postimg.cc/Ssn09sD4/icons8-double-right-96.png" alt=""></button>
        </span>
      </div>
      
    </div>
  </template>
   <script>
   export default {
    data() {
    return {
      visibleElement: 1,
      isHidden: true,
    };
  },
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
           if (duration.classList.contains('gallery-controls-previous')) {
             this.carouselArray.push(this.carouselArray.shift());
           } else {
             this.carouselArray.unshift(this.carouselArray.pop());
           }
           this.updateGallery();
         }
   
         setControls() {
           const buttons = galleryControlsContainer.querySelectorAll('button');
   
           buttons.forEach((button, index) => {
             if (index < this.carouselControls.length) {
               button.classList.add(`gallery-controls-${this.carouselControls[index]}`);
             }
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
     },
     methods:{
      show(elementNumber) {
      this.visibleElement = elementNumber;
    },
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
  /* z-index: 2; */
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
    /* this is for the placement of the cards */
    .gallery-item{
     height: 230px;
     opacity: 0;
     position: absolute;
     transition: all 0.3s ease-in-out;
     width: 330px;
     z-index: 0;
     border-radius: 15px;
     background-size: contain;
    }
    .gallery-item-1{
      left:-2%;
      opacity: .4 ;
      transform: translateX(-50%);
    }
    .gallery-item-2, .gallery-item-4{
      height: 280px;
      opacity: 0.8;
      width: 400px;
      z-index:1 ;
    }
    .gallery-item-2{
  left:22%;
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
      left: 102%;
      opacity: .4;
      transform: translateX(-50%);
  
    }
    /* this is for the styling of the buttons */
    .gallery-controls{
      display: flex;
      justify-content: center;
      margin:25px 0 ;
      height: 100px;
    }
  
    .previous, .next{
      height: 70px;
      margin: 160px;
      margin-top: 0;
      background-color:transparent;
      border: none;
      border-radius: 30px;
      width: 75px;
      transform: translateX(-13px);
    }
    .ctrl{
      height: 50px;
    }
    
     
  </style>
  