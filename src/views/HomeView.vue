<template>
  <div>
    <div class="boss">
      <div class="main">
        <div class="photo">
          <img
            class="header"
            src="https://i.postimg.cc/SsRKftR6/wallpaperflare-com-wallpaper.jpg"
          />
          <div class="text">
            <h1>Antonio Tone</h1>
          </div>
        </div>
      </div>
      <div class="row intro">
        <div class="col-6 text-center d-flex justify-content-start">
         <div class="head">
          Welcome to my digital playground, where pixels meet purpose and creativity knows no bounds. Explore the digital tapestry of my work, where innovation, design, and passion converge to craft extraordinary experiences
         </div>
        </div>
        <div class="col-6 text-center d-flex justify-content-center">
        <p class="sub">In the world of web design, my passion for design,<br> code, and interaction sets me apart and fuels my <br> creative edge.</p>
        </div>
        <div class="about d-flex justify-content-center mb-5">
          <hr class="mx-auto mt-5" />
          <magnetic class="btn text-center" buttonText="About" />
          <!-- <magnetic class="btn  text-center" buttonText="send"/> -->
        </div>
      </div>
      <div class=" d-flex justify-content-center">
      <button class="toggle" @click="show(1)">Portfolio</button>
      <button class="toggle" @click="show(2)">E-commerce</button>
      <button class="toggle" @click="show(3)">Appliance store</button>
      <button class="toggle" @click="show(4)">BMI</button>
      <button class="toggle" @click="show(5)">Rental</button>
      </div>
     <div class="">
      <div class="row prod" v-show="visibleElement === 1">
        <div class="col-6">
          <div class="card">
            <img class="img" src="https://i.postimg.cc/BbZ7zbhk/Screenshot-2023-10-30-144708.png" alt="">
  <div class="textBox">
<div class="d-flex justify-content-center">
  <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif" alt=""></button></a>
 <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/d1SJQh7P/output-onlinegiftools-1.gif" alt=""></button></a>
</div>
  </div>
</div>

        </div>
        <div class="col-6 work">
          <p class="text-center">my first Portfolio</p>
        </div>
      </div>
      <div class="row prod" v-show="visibleElement === 2">
        <div class="col-6">
          <div class="card">
            <img class="img" src="https://i.postimg.cc/Qt65mdvf/Screenshot-2023-10-30-150020.png" alt="">
  <div class="textBox">
<div class="d-flex justify-content-center">
  <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif" alt=""></button></a>
 <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/d1SJQh7P/output-onlinegiftools-1.gif" alt=""></button></a>

</div>
  </div>
</div>
        </div>
        <div class="col-6 work">
          <p class="text-center ">first e-commerce site</p>
        </div>
      </div>
      <div class="row prod" v-show="visibleElement === 3">
        <div class="col-6">
          <div class="card">
            <img class="img" src="https://i.postimg.cc/q7FCSvkq/Screenshot-2023-10-30-150857.png  " alt="">
  <div class="textBox">
<div class="d-flex justify-content-center">
  <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif" alt=""></button></a>
 <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/d1SJQh7P/output-onlinegiftools-1.gif" alt=""></button></a>

</div>
  </div>
</div>
        </div>
        <div class="col-6 work">
          <p class="text-center">group project</p>
        </div>
      </div>
      <div class="row prod" v-show="visibleElement === 4">
        <div class="col-6">
          <div class="card">
            <img class="img" src="https://i.postimg.cc/k5NgFMBL/Screenshot-2023-10-30-151253.png" alt="">
  <div class="textBox">
<div class="d-flex justify-content-center">
  <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif" alt=""></button></a>
 <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/d1SJQh7P/output-onlinegiftools-1.gif" alt=""></button></a>

</div>
  </div>
</div>
        </div>
        <div class="col-6 work">
          <p class="text-center">Fun little project i did</p>
        </div>
      </div>
      <div class="row prod" v-show="visibleElement === 5">
        <div class="col-6 d-flex justify-content-start">
          <div class="card">
            <img class="img" src="https://i.postimg.cc/sXvSnZ7v/Screenshot-2023-10-30-151739.png" alt="">
  <div class="textBox">
<div class="d-flex justify-content-center">
  <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif" alt=""></button></a>
 <a href=""><button class="toggle linkBg"><img class=" links" src="https://i.postimg.cc/d1SJQh7P/output-onlinegiftools-1.gif" alt=""></button></a>

</div>
  </div>
</div>
        </div>
        <div class="col-6 work">
          <p class="text-center">Capstone project</p>
        </div>
      </div>
     </div>

      <section class="holder mb-5 mx-auto">
        <div class="horizontal_item container p-5">
          <div class="row row-1">
            <div class="flex-col m-2" >
              <div class="horizontal-single-item">
                <div class="d-flex justify-content-center">
                  <img
                    class="profile"
                    src="https://i.postimg.cc/VL53dhfv/C12-Luke-Evertson-1.jpg"
                    alt="picture"
                  />
                </div>
                <div class="text-center">
                  <p class="name mx-auto">Luke Evertson</p>
                  <p class="test autotype">
                    Antonio is a very fun person to work with and has a great sense of humour.He Is hardworking and disciplined.He could be a role model for many
                    </p>
                </div>
              </div>
            </div>
            <div class="flex-col m-2">
              <div class="horizontal-single-item">
                <div class="d-flex justify-content-center">
                  <img
                    class="profile"
                    src="https://i.postimg.cc/7P5FLcY6/C12-Asiphe-Ndimlana-1.jpg"
                    alt="picture"
                  />
                </div>
                <div class="text-center">
                  <p class="name mx-auto">Asiphe Ndimlana</p>
                  <p class="test autotype">                  
                    Antonio is very independent. Whenever he struggles with something he would rather first try and figure it out himself before asking for help. He is extremely kind and friendly and turns every person he meets for the first time into his friend.
                  </p>
                </div>
              </div>
            </div>
            <div class="flex-col m-2">
              <div class="horizontal-single-item">
                <div class="d-flex justify-content-center">
                  <img
                    class="profile"
                    src="https://i.postimg.cc/dVNRDW0s/C12-Taahirah-Ismail-1.jpg"
                    alt="picture"
                  />
                </div>
                <div class="text-center">
                  <p class="name mx-auto">Taahirah Ismail</p>                    
                  <p class="test autotype">
                    He may be a man of few words, but Antonio's hard work and dedication always shine through in whatever he does. You can easily tell he appreciates every opportunity he is given and takes nothing for granted
                  </p>
                </div>
              </div>
            </div>
            <div class="flex-col m-2">
              <div class="horizontal-single-item">
                <div class="d-flex justify-content-center">
                  <img
                    class="profile"
                    src="https://i.postimg.cc/DyHztfG2/IMG-9863-1.jpg"
                    alt="picture"
                  />
                </div>
                <div class="text-center">
                  <p class="name mx-auto">Ethan Oliver</p>
                  <p class="test autotype">
                    I am thrilled to share my positive testimonial about my experience with Antonio. From the moment I first met him I was impressed. His dedication to excellence and drive to achieve was evident in every interaction I had with him.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="row row-2 second">
            <div class="flex-col m-2">
              <div class="horizontal-single-item">
                <div class="d-flex justify-content-center">
                  <img
                    class="profile"
                    src="https://i.postimg.cc/7YYT7gdf/Screenshot-2023-05-11-111514.png"
                    alt="picture"
                  />
                </div>
                <div class="text-center">
                  <p class="name mx-auto">Deno Rautenbach</p>
                  <p class="test autotype">                   
                    Antonio is a very hardworking individual.He has improved a lot in both his coding aswell as in his problem solving skills. He is an extremely nice person to work with as he is very friendly
                  </p>
                </div>
              </div>
            </div>
            <div class="flex-col m-2">
              <div class="horizontal-single-item">
                <div class="d-flex justify-content-center">
                  <img
                    class="profile"
                    src="https://i.postimg.cc/mk1J6c6M/Screenshot-2023-07-05-161952.png"
                    alt="picture"
                  />
                </div>
                <div class="text-center">
                  <p class="name mx-auto">Maxwill Isaacs</p>
                  <p class="test autotype">                    
                    Antonio is an exceptionally hard worker and always making time to assist anyone who is in need. Also goes the extra-mile when doing anything that has to be done. He is also very confident in his capabilities and never fails to get the Job done.
                  </p>
                </div>
              </div>
            </div>
            <div class="flex-col m-2">
              <div class="horizontal-single-item">
                <div class="d-flex justify-content-center">
                  <img
                    class="profile"
                    src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg"
                    alt="picture"
                  />
                </div>
                <div class="text-center">
                  <p class="test">
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                    Eveniet reiciendis et facilis fugit repellat! Voluptatibus,
                    dignissimos tempore dolorum ipsam deleniti optio mollitia
                    minima aspernatur porro quis error sit veniam unde?
                  </p>
                </div>
              </div>
            </div>
            <div class="flex-col m-2">
              <div class="horizontal-single-item">
                <div class="d-flex justify-content-center">
                  <img
                    class="profile"
                    src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg"
                    alt="picture"
                  />
                </div>
                <div class="text-center">
                  <p class="test">
                    Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                    Eveniet reiciendis et facilis fugit repellat! Voluptatibus,
                    dignissimos tempore dolorum ipsam deleniti optio mollitia
                    minima aspernatur porro quis error sit veniam unde?
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
    </section>
    </div>
  </div>
</template>
<script>
// import _ from "lodash";
// import Lenis from "@studio-freight/lenis";
import { gsap } from 'gsap';
import { ScrollTrigger } from 'gsap/ScrollTrigger';
import magnetic from "../components/magButtonComp.vue";
export default {
  components: {
    magnetic,
  },
  data() {
    return {
      box_items: [],
      visibleElement: 1,
      lenis: null,
    };
  },
  mounted() {
    this.autoType();
    
    gsap.registerPlugin(ScrollTrigger);
    const container = this.$el.querySelector('.holder');
    const row2 = this.$el.querySelector('.row-1');
    const itemsRow1 = gsap.utils.toArray('.row-1 .flex-col');
    const itemsRow2 = gsap.utils.toArray('.row-2 .flex-col');
    const totalWidth = (itemsRow1.length + itemsRow2.length) * 500;

    gsap.to(itemsRow1, {
      xPercent: -100 * (itemsRow1.length - 1),
      ease: 'sine.out',
      scrollTrigger: {
        trigger: container,
        markers:true,
        pin: false,
        pinSpacing: false,
        scrub: 4,
        snap: 0.5 / (itemsRow1.length - 1),
        end: `+=${totalWidth}`,
      },
    });
    // scrollTrigger.progress(1);

    gsap.to(itemsRow2, {
      xPercent: 100 * (itemsRow2.length - 1),
      ease: 'sine.out',
      scrollTrigger: {
        trigger: row2,
        pin: false,
        pinSpacing: false,
        scrub: 4,
        snap: 0.5 / (itemsRow2.length - 1),
        end: `+=${totalWidth}`,
      },
    });

  },

  methods: {
    show(elementNumber) {
      this.visibleElement = elementNumber;
    },
    autoType() {
      const text = document.querySelector('.autotype');
      const originalText = text.textContent;
      
      const textLoad = () => {
        let i = 0;
        const intervalId = setInterval(() => {
          text.textContent = originalText.slice(0, i);
          i+=2;
          if (i > originalText.length) {
            clearInterval(intervalId);
          }
        }, 100); // Adjust the interval to control the typing speed
      };
      setTimeout(() => {
        
      }, 2000);

      textLoad();
      setInterval(textLoad, 12000);
    },
  },
   
    //lenis smooth scroll setup
    // smoothScroll() {
      // Use the 'lenis' instance created in 'mounted'
      // this.lenis.options.duration =0.5;
      // this.lenis.options.easing = (t) => Math.min(1, 1.001 - Math.pow(2, -10 * t));

      // const raf = (time) => {
      //   this.lenis.raf(time);
      //   requestAnimationFrame(raf);
      // };

      // function raf(time) {
      //   this.lenis.raf(time);
      //   requestAnimationFrame(raf);
      // }

      // requestAnimationFrame(raf);
    // },
  };

</script>
<style scoped>
.main {
  position: relative;
  min-height: 100vh !important;
}
.header {
  z-index: 0;
  position: absolute;
  min-width: 100% !important;
  height: 100% !important;
}
.text {
  z-index: 3;
  position: absolute;
  top: 70%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.intro {
  width: 100% !important;
  top: 900px !important;
  padding: 120px;
}
.head {
  font-size: x-large !important;
  display: block !important;
}
.sub {
  font-size: medium;
  display: block !important;
   margin-top: 2em;
    margin-bottom: 1em;
    margin-left: 0;
    margin-right: 0;
    

}
.work{
  display: flex;
  flex-direction: column !important;
  align-items: center;
  justify-content: center;
}
hr {
  position: relative;
  width: 50% !important;
}
.about {
  position: relative;
}
.btn {
  position: absolute;
  z-index: 3;
  bottom: -60% !important;
  left: 65%;
}
.toggle{
  margin: 5px;
  padding: 5px;
  width: 100px;
  border-radius: 30px;
color: aliceblue;
  background: radial-gradient(circle at 24.1% 68.8%, rgb(50, 50, 50) 0%, rgb(0, 0, 0) 99.4%);
  cursor: pointer !important;
  border: none !important;

}
.prod {
  padding: 100px;
}
.image {
  height: 250px;
  width: 450px;
 
}
.profile {
  height: 45px;
  width: 45px;
  border-radius: 999px;
  animation: outerglow 1s alternate infinite cubic-bezier(0.65, 0.05, 0.36, 1);
}
@keyframes outerglow {
  0% {
    box-shadow: 0px 0px 0px blue;
  }
  100% {
    box-shadow: 0px 0px 15px blue;
  }
}

.test {
  font-size: small;
}
.luke::after{
  /* content:""; */
  /* width:100%;
  height:100%;
  background-color:#010718;
  position:absolute;
  left: 0;
  top:0;
  border-left:3px solid #73EEDC; */
  /* animation:animate; */
}
/* @keyframes animate{
  40%,60%{
    left:calc(100% + 4px);
  }
  100%{
    left:-13px;
  }
} */
.container {
  max-width: 100em;
  background-color: black;
 
}
.wrapper {
  padding: 20px;
  /* background-color: greenyellow; */
}
.flex-col {
  background-color: burlywood;
  padding: 20px;
  height: 250px;
  width: 300px;
}
.links{
 height: 30px;
}
.linkBg{
  background-color: transparent !important;
}



.card {
  width: 600px;
  height: 285px;
  background: #313131;
  border-radius: 20px;
  ;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: white;
  transition: 0.2s ease-in-out;
}
.holder{
 background-color: yellowgreen;
 /* width: 300%; */
 /* right: 50%; */
 height: 700px;
 display: flex;
 justify-content: center;
 align-items: center;
 padding: 0;
  margin-bottom: 900px !important;
}
.row-1{
  background-color: blueviolet;
  /* width: 300% !important; */
  width: 120vw;
    right: 10vw;

}
.row-2{
  background-color: paleturquoise;
  width: 120vw;
    right: 120vw;

  /* width: 300% !important; */
}

.img {
  border-radius: 20px;
  width: 600px;
  height: 285px;
  position: absolute;
  transition: 0.2s ease-in-out;
  z-index: 1;
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
  height: 100%;
  filter: blur(7px);
  /* animation: anim 3s infinite; */
}
.card:hover{
  animation: anim 3s infinite;
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

.card:hover {
  transform: scale(1.04);
}

.horizontal_content{
  display: flex;
}



</style>