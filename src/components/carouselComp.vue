<template>
  <div>
    <div class="testimonials">
      <swiper
    :effect="'coverflow'"
    :grabCursor="true"
    :centeredSlides="true"
    :slidesPerView="'auto'"
     :loop="true"
     :autoplay=3000
     :parallax="true"
     :speed=800
    :modules="modules"
    :pagination="{
      clickable: true,
      el:'.swiper-pagination'
    }"
   
    
    class="mySwiper swiper-container"
  >
    <swiper-slide class="swiper-slide">
      <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            Lorem Ipsum has been the industry's standard dummy text ever since
           the 1500s, when an unknown printer took a galley of type and
           scrambled it to make a type specimen book.</p
         >
         <div class="imgBx">
           <img
         src="https://swiperjs.com/demos/images/nature-10.jpg" />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Bernadette Newman <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div>
      </swiper-slide>

        <swiper-slide class="swiper-slide">
      <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            Lorem Ipsum has been the industry's standard dummy text ever since
           the 1500s, when an unknown printer took a galley of type and
           scrambled it to make a type specimen book.</p
         >
         <div class="imgBx">
           <img
           src="https://images.unsplash.com/photo-1477085547885-8ee2d26e4efa?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxNDU4OXwwfDF8cmFuZG9tfHx8fHx8fHx8MTY0MzA4MTY5Nw&ixlib=rb-1.2.1&q=85">
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Bernadette Newman <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div>
      </swiper-slide>
        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            Lorem Ipsum has been the industry's standard dummy text ever since
           the 1500s, when an unknown printer took a galley of type and
           scrambled it to make a type specimen book.</p
         >
         <div class="imgBx">
           <img
           src="https://images.unsplash.com/photo-1496335659881-42cabe4a5f2c?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxNDU4OXwwfDF8cmFuZG9tfHx8fHx8fHx8MTY0MzA4MTcxNw&ixlib=rb-1.2.1&q=85">
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Bernadette Newman <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div></swiper-slide>
        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            Lorem Ipsum has been the industry's standard dummy text ever since
           the 1500s, when an unknown printer took a galley of type and
           scrambled it to make a type specimen book.</p
         >
         <div class="imgBx">
           <img
           src="https://images.unsplash.com/photo-1617339847756-976edbc411e7?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxNDU4OXwwfDF8cmFuZG9tfHx8fHx8fHx8MTY0MzA4MTczNw&ixlib=rb-1.2.1&q=85"
  />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Bernadette Newman <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div></swiper-slide>
        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            Lorem Ipsum has been the industry's standard dummy text ever since
           the 1500s, when an unknown printer took a galley of type and
           scrambled it to make a type specimen book.</p
         >
         <div class="imgBx">
           <img
           src="https://images.unsplash.com/photo-1482498081626-c0d36d9c5ab9?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxNDU4OXwwfDF8cmFuZG9tfHx8fHx8fHx8MTY0MzA4MTc2NA&ixlib=rb-1.2.1&q=85"
  />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Bernadette Newman <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div></swiper-slide
        >
        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            Lorem Ipsum has been the industry's standard dummy text ever since
           the 1500s, when an unknown printer took a galley of type and
           scrambled it to make a type specimen book.</p
         >
         <div class="imgBx">
           <img
           src="https://images.unsplash.com/photo-1473707669572-40d832255b5e?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxNDU4OXwwfDF8cmFuZG9tfHx8fHx8fHx8MTY0MzA4MTc4MA&ixlib=rb-1.2.1&q=85"
  />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Bernadette Newman <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div></swiper-slide>
        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            Lorem Ipsum has been the industry's standard dummy text ever since
           the 1500s, when an unknown printer took a galley of type and
           scrambled it to make a type specimen book.</p
         >
         <div class="imgBx">
           <img
         src="https://swiperjs.com/demos/images/nature-4.jpg" />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Bernadette Newman <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div>
    </swiper-slide>

        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            Lorem Ipsum has been the industry's standard dummy text ever since
           the 1500s, when an unknown printer took a galley of type and
           scrambled it to make a type specimen book.</p
         >
         <div class="imgBx">
           <img
         src="https://swiperjs.com/demos/images/nature-5.jpg" />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Bernadette Newman <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div>
      </swiper-slide>

        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            Lorem Ipsum has been the industry's standard dummy text ever since
           the 1500s, when an unknown printer took a galley of type and
           scrambled it to make a type specimen book.</p
         >
         <div class="imgBx">
           <img
         src="https://swiperjs.com/demos/images/nature-6.jpg" />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Bernadette Newman <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div>        </swiper-slide>
        <div class="swiper-pagination"></div>

     
  </swiper>

  
  </div>
  </div>
</template>
<script>
  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';

  import 'swiper/css/effect-coverflow';
  import 'swiper/css/pagination';


  // import required modules
  import { EffectCoverflow, Pagination } from 'swiper/modules';

  export default {
    components: {
      Swiper,
      SwiperSlide,
    },
    setup() {
      return {
        modules: [EffectCoverflow, Pagination],
      };
    },
    mounted() {
     this.autoType(); 
    },
    methods:{
      autoType() {
      this.$nextTick(() => {
        const textElements = document.querySelectorAll(".autotype");

        textElements.forEach((textElement) => {
          const originalText = textElement.textContent;
          let i = 0;

          function typeText() {
            const intervalId = setInterval(() => {
              textElement.textContent = originalText.slice(0, i);
              i += 3;
              if (i > originalText.length) {
                clearInterval(intervalId);
                setTimeout(() => {
                  // Reset the text and call typeText again after a delay

                  i = 0;
                  setTimeout(typeText, 20000); // Adjust the delay as needed
                }, 10000); // Adjust the delay between loops as needed
              }
            }, 100); // Adjust the interval to control the typing speed
          }

          typeText(); // Start the typing animation
        });
      });
    },
    }
  };
</script>
<style scoped>
.testimonials{
  position: relative;
  max-width: 100%;
}
.testimonials::after{
  content: "";
  position: relative;
  top: 100%;
  left: 0;
  width: 100%;
  height: 50px; /* Height of the reflection */
  background: linear-gradient(180deg, rgba(0, 0, 0, 0.2) 0%, rgba(0, 0, 0, 0.1) 50%, rgba(0, 0, 0, 0) 100%) !important;
  pointer-events: none;
}
.testimonials .card{
  position: relative;
  width:100%;
  height: 350px !important;
  margin:0 auto;
  background: #333;
  padding:60px 40px;
  text-align: center;
  overflow: hidden;
}
.testimonials .card .layer{
  position: absolute;
  top:0;
  left: 0;
  width:100%;
  height:100%;
  background: linear-gradient(#03a9f4,#e91ee3);
  z-index: 1;
  top:calc(100% - 2px);
  transition:0.5s;
}
.testimonials .card:hover .layer{
 top:0;
}
.testimonials .card .content{
  position: relative;
  z-index: 2;
}
.caption{
  font-size: 18px;
  line-height: 24px;
  margin-bottom: 20px;
  color:white;
}
.details > h2{
  font-size: 18px;
  color: white;
}
.details > h2 > span{
  color:#03a9f4;
  font-size: 14px;
  transition: 0.5s;
}
.testimonials .card:hover .content .details h2 span{
  color:white;
}

.swiper-button-prev {
  transform: translateX(50px);
}
.swiper-button-next {
  transform: translateX(-50px);
}
  #app { height: 100% }
html,
body {
  position: relative;
  height: 100%;
}

body {
  background: #eee;
  font-family: Helvetica Neue, Helvetica, Arial, sans-serif;
  font-size: 14px;
  color: #000;
  margin: 0;
  padding: 0;
}

.swiper {
  width: 100%;
  padding-top: 50px;
  padding-bottom: 50px;
}

.swiper-slide {
  min-height: 350px !important;
  width:350px;
  background-position: center;
  background-size: cover;
  /* margin: 0 20px; */
}

.swiper-slide img {
  display: block;
  width: 100%;
}
img{
  height: 100px !important;
  width:100px !important;
  margin: 0 auto;
  border-radius: 50%;
  overflow: hidden;
  border:4px solid white;
}

.swiper-pagination{
}

</style>
