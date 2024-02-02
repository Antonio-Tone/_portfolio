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
            "Antonio is one determined ,dedicated team member to have on
                  any team, he gets the job done and always to lend a hand to
                  make sure the whole team are on the same page."</p
         >
         <div class="imgBx">
           <img
         src="https://i.ibb.co/VN5GnRf/Screenshot-2023-11-08-130937.png" />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Tara Snell <br/><span>Colleague</span>
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
            "Antonio is a very fun person to work with and has a great
                  sense of humour.He Is hardworking and disciplined.He could be
                  a role model for many."</p
         >
         <div class="imgBx">
           <img
           src="https://i.ibb.co/1732hhr/C12-Luke-Evertson-1.jpg">
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Luke Evertson <br/><span>Colleague</span>
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
                 "Antonio's hard work and
                  dedication always shine through in whatever he does.He appreciates every opportunity he is given and
                  takes nothing for granted."</p
         >
         <div class="imgBx">
           <img
           src="https://i.ibb.co/P9mRfj0/C12-Taahirah-Ismail-1.jpg">
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Taahirah Ismail <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div></swiper-slide>
        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
            "Antonio is very independent. Whenever he struggles with
                  something he would rather first try and figure it out himself
                  before asking for help. It is always a pleasure to work with him"</p
         >
         <div class="imgBx">
           <img
           src="https://i.ibb.co/7bBN0xC/C12-Asiphe-Ndimlana-1.jpg"
  />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Asiphe Ndimlana <br/><span>Colleague</span>
          </h2>
          </div>
        </div>
      </div></swiper-slide>
        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype">
                  "From the moment I first met him I was
                  impressed. His dedication to excellence and drive to achieve
                  was evident in every interaction I had with him."</p
         >
         <div class="imgBx">
           <img
           src="https://i.ibb.co/GF0JgVX/IMG-9863-1.jpg"
  />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Ethan Oliver <br/><span>Colleague</span>
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
            " Antonio is a very hardworking individual.He has improved a
                  lot in both his coding aswell as in his problem solving
                  skills. He is an extremely nice person to work with as he is
                  very friendly"</p
         >
         <div class="imgBx">
           <img
           src="https://i.ibb.co/b2mpXYK/Screenshot-2024-01-23-094052.png"
  />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Deno Rautenbach <br/><span>Assistant lecturer</span>
          </h2>
          </div>
        </div>
      </div></swiper-slide>
        <swiper-slide class="swiper-slide">
          <div class="card">
        <div class="layer"></div>
         <div class="content">
           <p class="caption autotype her">
            "Working alongside Antonio on several IT ventures has been an
                  absolute pleasure. His precision-oriented approach coupled
                  with his knack for troubleshooting is highly commendable."</p
         >
         <div class="imgBx">
           <img
         src="https://i.ibb.co/WWrMcvj/C12-Ayesha-Galant-Class1-1.jpg" />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
          Ayesha Galant <br/><span>Colleague</span>
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
            "Antonio is an exceptionally hard worker and always making
                  time to assist anyone who is in need. Also goes the extra-mile
                  when doing anything that has to be done."</p
         >
         <div class="imgBx">
           <img
         src="https://i.ibb.co/dLW0kTV/Screenshot-2024-01-23-094836.png" />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
            Maxwill Isaacs <br/><span>Colleague</span>
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
            "Antonio is an exceptional professional, with deep expertise,
                  dedication, and strong problem-solving skills.His work ethic,
                   and collaborative nature make him a remarkable team player".</p
         >
         <div class="imgBx">
           <img
         src="https://i.ibb.co/xjgWbwS/Screenshot-2023-10-04-154441-1.png" />
 
         </div>
          <div class="details">
          <h2
            class="title"
           
          >
          Ganiefah Majiet <br/><span>Colleague</span>
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
  font-size: 15px;
  line-height: 24px;
  margin-bottom: 20px;
  color:white;
}
.her{
  font-size: 14px !important;
}
.details > h2{
  font-size: 20px !important;
  color: white;
}
.details > h2 > span{
  color:#03a9f4;
  font-size: 15px;
  transition: 0.5s;
}
.testimonials .card:hover .content .details h2 span{
  color:white;
}
.imgBx, .details{
  position: relative;
  /* top:5% ; */
  transform: translateY(18px) !important;
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
