<template>
  <div>
    <div class="gallery">
      <div class="gallery-container">
        <div
          v-for="index in 5"
          :key="index"
          class="gallery-item"
          :class="'gallery-item-' + index"
          :style="{
            transform: 'translateX(' + ((index - visibleElement + 5) % 5 - 2) * 100 + '%)',
            zIndex: index === visibleElement ? 2 : 1,
            opacity: index === visibleElement ? 1 : 0.5,
            // filter: index === visibleElement ? 'none' : 'blur(5px)',
          }"
        >
          <!-- Replace this block with your card content -->
          <div class="card">
            <h3>Card {{ index }}</h3>
            <p>Card content goes here...</p>
          </div>
        </div>
      </div>
      <span class="gallery-controls">
        <button class="previous" @click="updateActiveClass('previous')">
          <img class="ctrl" src="https://i.postimg.cc/zXcxLj4y/icons8-double-left-96.png" alt="" />
        </button>
        <button class="next" @click="updateActiveClass('next')">
          <img class="ctrl" src="https://i.postimg.cc/Ssn09sD4/icons8-double-right-96.png" alt="" />
        </button>
      </span>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      visibleElement: 3, // Set the initial visible card to card 3
    };
  },
  methods: {
    updateActiveClass(direction) {
      // Logic to update the active class in a loop with smooth transitions
      const totalCards = 5;
      if (direction === 'previous') {
        this.visibleElement = (this.visibleElement - 1 + totalCards) % totalCards || totalCards;
      } else {
        this.visibleElement = (this.visibleElement + 1) % (totalCards + 1) || 1;
      }
    },
  },
};
</script>

<style scoped>
/* Add your styling for cards and other elements here */
.gallery-container {
  display: flex;
  transition: transform 0.5s ease-in-out;
}

.gallery-item {
  flex: 0 0 100%;
  transform-style: preserve-3d;
  transition: transform 0.5s ease-in-out, opacity 0.5s ease-in-out, z-index 0.5s ease-in-out, filter 0.5s ease-in-out;
}

.card {
  border: 1px solid #ccc;
  padding: 10px;
  margin: 10px;
  text-align: center;
  transform: translateZ(50px); /* Adjust the depth of the 3D effect */
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
  /* z-index: ; */
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
      box-shadow: -2px 5px 33px 6px rgba(0,0,0.35);

      left:30%;
      opacity: .4 ;
      transform: translateX(-50%);
    }
    .gallery-item-1, .gallery-item-5{
height: 350px;
width: 300px;

    }
    .gallery-item-2, .gallery-item-4{
      height: 400px;
      opacity: 0.8;
      width: 320px;
      z-index:1 ;
    }
    .gallery-item-2{
  box-shadow: -2px 5px 33px 6px rgba(0,0,0.35);

  left:28%;
  transform: translateX(-50%);
    }
    .gallery-item-3{
    box-shadow: -2px 5px 33px 6px rgba(0,0,0.35);
    height: 450px;
    width:350px;
    opacity: 1;
    left:28%;
    transform: translateX(-50%);
    z-index: 30 !important;
    }
    .gallery-item-4{
      box-shadow: -2px 5px 33px 6px rgba(0,0,0.35);
  left: 30%;
   transform: translateX(-50%);
    }
    .gallery-item-5{
      box-shadow: -2px 5px 33px 6px rgba(0,0,0.35);
      left: 30%;
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
  