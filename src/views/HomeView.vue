<template>
 <div class="boss">
      <!-- hero section -->

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
      <!--introduction -->

      <div class="row intro">
        <div class="col-6 text-center d-flex justify-content-start">
          <div class="head">
            Welcome to my digital playground, where pixels meet purpose and
            creativity knows no bounds. Explore the digital tapestry of my work,
            where innovation, design, and passion converge to craft
            extraordinary experiences
          </div>
        </div>
        <div class="col-6 text-center d-flex justify-content-center">
          <p class="sub">
            In the world of web design, my passion for design,<br />
            code, and interaction sets me apart and fuels my <br />
            creative edge.
          </p>
        </div>
        <div class="about d-flex justify-content-center mb-5">
          <hr class="mx-auto mt-5" />
          <magnetic class="btn text-center" buttonText="About" />
        </div>
      </div>
      <!--projects section -->

      <div class="projects">
        <div class="d-flex justify-content-center">
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
                <img
                  class="img"
                  src="https://i.postimg.cc/BbZ7zbhk/Screenshot-2023-10-30-144708.png"
                  alt=""
                />
                <div class="textBox">
                  <div class="d-flex justify-content-center">
                    <a href=""
                      ><button class="toggle linkBg">
                        <img
                          class="links"
                          src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif"
                          alt=""
                        /></button
                    ></a>
                    <a href=""
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
            </div>
            <div class="col-6 work">
              <p class="text-center">my first Portfolio</p>
            </div>
          </div>
          <div class="row prod" v-show="visibleElement === 2">
            <div class="col-6">
              <div class="card">
                <img
                  class="img"
                  src="https://i.postimg.cc/Qt65mdvf/Screenshot-2023-10-30-150020.png"
                  alt=""
                />
                <div class="textBox">
                  <div class="d-flex justify-content-center">
                    <a href=""
                      ><button class="toggle linkBg">
                        <img
                          class="links"
                          src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif"
                          alt=""
                        /></button
                    ></a>
                    <a href=""
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
            </div>
            <div class="col-6 work">
              <p class="text-center">first e-commerce site</p>
            </div>
          </div>
          <div class="row prod" v-show="visibleElement === 3">
            <div class="col-6">
              <div class="card">
                <img
                  class="img"
                  src="https://i.postimg.cc/q7FCSvkq/Screenshot-2023-10-30-150857.png  "
                  alt=""
                />
                <div class="textBox">
                  <div class="d-flex justify-content-center">
                    <a href=""
                      ><button class="toggle linkBg">
                        <img
                          class="links"
                          src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif"
                          alt=""
                        /></button
                    ></a>
                    <a href=""
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
            </div>
            <div class="col-6 work">
              <p class="text-center">group project</p>
            </div>
          </div>
          <div class="row prod" v-show="visibleElement === 4">
            <div class="col-6">
              <div class="card">
                <img
                  class="img"
                  src="https://i.postimg.cc/k5NgFMBL/Screenshot-2023-10-30-151253.png"
                  alt=""
                />
                <div class="textBox">
                  <div class="d-flex justify-content-center">
                    <a href=""
                      ><button class="toggle linkBg">
                        <img
                          class="links"
                          src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif"
                          alt=""
                        /></button
                    ></a>
                    <a href=""
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
            </div>
            <div class="col-6 work">
              <p class="text-center">Fun little project i did</p>
            </div>
          </div>
          <div class="row prod" v-show="visibleElement === 5">
            <div class="col-6 d-flex justify-content-start">
              <div class="card">
                <img
                  class="img"
                  src="https://i.postimg.cc/sXvSnZ7v/Screenshot-2023-10-30-151739.png"
                  alt=""
                />
                <div class="textBox">
                  <div class="d-flex justify-content-center">
                    <a href=""
                      ><button class="toggle linkBg">
                        <img
                          class="links"
                          src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif"
                          alt=""
                        /></button
                    ></a>
                    <a href=""
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
            </div>
            <div class="col-6 work">
              <p class="text-center">Capstone project</p>
            </div>
          </div>
        </div>
      </div>
      <!-- testimonials -->

      <section class="holder  mx-auto">
        <div class="horizontal_item container">
          <div class="row row-1">
            <div class="flex-col m-2">
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
                    Antonio is a very fun person to work with and has a great
                    sense of humour.He Is hardworking and disciplined.He could
                    be a role model for many
                  </p>
                </div>
              </div>
            </div>
            <div class="flex-col m-2">
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
                    Antonio is a very fun person to work with and has a great
                    sense of humour.He Is hardworking and disciplined.He could
                    be a role model for many
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
                    Antonio is very independent. Whenever he struggles with
                    something he would rather first try and figure it out
                    himself before asking for help. He is extremely kind and
                    friendly and turns every person he meets for the first time
                    into his friend.
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
                    He may be a man of few words, but Antonio's hard work and
                    dedication always shine through in whatever he does. You can
                    easily tell he appreciates every opportunity he is given and
                    takes nothing for granted
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
                    I am thrilled to share my positive testimonial about my
                    experience with Antonio. From the moment I first met him I
                    was impressed. His dedication to excellence and drive to
                    achieve was evident in every interaction I had with him.
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
                    Antonio is a very hardworking individual.He has improved a
                    lot in both his coding aswell as in his problem solving
                    skills. He is an extremely nice person to work with as he is
                    very friendly
                  </p>
                </div>
              </div>
            </div>
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
                    Antonio is a very hardworking individual.He has improved a
                    lot in both his coding aswell as in his problem solving
                    skills. He is an extremely nice person to work with as he is
                    very friendly
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
                    Antonio is an exceptionally hard worker and always making
                    time to assist anyone who is in need. Also goes the
                    extra-mile when doing anything that has to be done. He is
                    also very confident in his capabilities and never fails to
                    get the Job done.
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
      <!-- contact section -->

      <section class="contact">
        <div class="d-flex justify-content-center heading">
            <img class="profile" src="https://i.postimg.cc/y6cxh6tZ/T02-LW4-RMXJQ-U051-ZHJ00-N9-edefadf5b7cb-512.png" alt="">
            <h1  class="connect">Let's get in<br><span class="shift">touch</span><span class="">...</span></h1>
        </div>
        <div class="d-flex justify-content-center">
          <hr class="hr">
          <magnetic class="switch" buttonText="Contact"/>
        </div>
        <div class="d-flex justify-content-center">
          <span class="info">Antoniotone815@gmail.com</span><span class="info">065 851 3653</span>
        </div>
        <div class="row footer">
         <div class="col-6 general">
          <div class="">
            <div class=""><span>Version:</span></div>
            <div class="">2023© Edition</div>
          </div>
         </div>
          <div class="col-6 socials">
            <div class="">
            <div class=""><span>Socials:</span></div>
            <div class="wrapper d-flex justify-content-center p-0">
              <a href="https://www.linkedin.com/in/antonio-tone-220925281" target="_blank" class="link">Linkdin</a>
              <a href="" class="link">Facebook</a>
              <a href="" class="link">Instagram</a>
            </div>
          </div>
          </div>
        </div>
      </section>
    </div>
</template>
<script>
// import _ from "lodash";
// import Lenis from "@studio-freight/lenis";
import { gsap } from "gsap";
import { ScrollTrigger } from "gsap/ScrollTrigger";
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
    const container = this.$el.querySelector(".holder");
    const row2 = this.$el.querySelector(".holder");
    const itemsRow1 = gsap.utils.toArray(".row-1 .flex-col");
    const itemsRow2 = gsap.utils.toArray(".row-2 .flex-col");
    const totalWidth = (itemsRow1.length + itemsRow2.length) * 300;

    gsap.to(itemsRow1, {
      xPercent: -100 * (itemsRow1.length - 1),
      ease: "linear",
      duration: 3,
      scrollTrigger: {
        start: "center center",
        trigger: container,
        pin: false,
        pinSpacing: false,
        scrub: 5,
        snap: 0.5 / (itemsRow1.length - 1),
        end: `+=${totalWidth}`,
      },
    });

    gsap.to(itemsRow2, {
      xPercent: 100 * (itemsRow2.length + 1),
      ease: "linear",
      duration: 3,
      scrollTrigger: {
        start: "center center",
        trigger: row2,
        pin: false,
        pinSpacing: false,
        scrub: 5,
        snap: 0.5 / (itemsRow2.length + 1),
        end: `+=${totalWidth}`,
      },
    });
  },

  methods: {
    show(elementNumber) {
      this.visibleElement = elementNumber;
    },
    autoType() {
      const text = document.querySelector(".autotype");
      const originalText = text.textContent;

      const textLoad = () => {
        let i = 0;
        const intervalId = setInterval(() => {
          text.textContent = originalText.slice(0, i);
          i += 2;
          if (i > originalText.length) {
            clearInterval(intervalId);
          }
        }, 100); // Adjust the interval to control the typing speed
      };
      setTimeout(() => {}, 2000);

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
.work {
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
.toggle {
  margin: 5px;
  padding: 5px;
  width: 100px;
  border-radius: 30px;
  color: aliceblue;
  background: radial-gradient(
    circle at 24.1% 68.8%,
    rgb(50, 50, 50) 0%,
    rgb(0, 0, 0) 99.4%
  );
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
  margin-top: 4px;
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


.container {
  max-width: 100em;

}
.horizontal-single-item{
  background: radial-gradient(circle at 24.1% 68.8%, rgb(50, 50, 50) 0%, rgb(0, 0, 0) 99.4%);  height: 210px;
}
.wrapper {
  padding: 20px;
}
.flex-col {
  background: radial-gradient(circle at 24.1% 68.8%, rgb(50, 50, 50) 0%, rgb(0, 0, 0) 99.4%);  
  color:lightgray;
  padding: 20px;
  height: 250px;
  width: 360px;
  text-align: center !important;
}
.links {
  height: 30px;
}
.linkBg {
  background-color: transparent !important;
}

.card {
  width: 600px;
  height: 285px;
  background: #313131;
  border-radius: 20px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: white;
  transition: 0.2s ease-in-out;
}
.holder {
  height: 700px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0;
  /* margin-bottom: 900px !important;A */
}
.row-1 {
  width: 200vw;
}
.row-2 {
  width: 200vw;
  transform: translateX(-12%);
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
.card:hover {
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

.contact{
  background: rgb(28,29,32);
  height: 730px;
}
.heading{
  transform:translateX(-350px) translateY(120px);
}
.connect{
  font-size: 4rem;
  margin-left: 10px !important;
}
.heading > .profile{
  height: 75px;
  width: 75px;
  border-radius: 999px;
  transform: translateY(75px) translateX(85px);
}
.shift{
 margin-left: 90px;
}

.hr{

  transform: translateY(200px);
  width: 65% !important;
}
.switch{
  transform: translateY(160px) translateX(-290px);
  z-index: 3;
  
 
}
.info{
  transform: translateY(160px) translateX(-290px);
  margin-right: 2rem;
  border: 1px solid white;
  padding: 15px;
  border-radius: 30px;
  transition: 2s ease-in-out;
}
.info:hover{
  background-color: red;
  cursor:pointer !important;
}
.footer{
  transform: translateY(300px) !important;

}
.general{
 transform:   translateX(150px);
  display: flex;
  flex-direction: column;
  align-items: start;
}
.socials{
   transform: translateX(-150px) ; 
  display: flex;
  flex-direction: column;
  align-items: end;
  justify-content: end;
}
.link{
 text-decoration: none;
 color: white;
 margin-right: 5px;
 transition: 1s ease-in-out;
 padding: 5px;
}

.link:hover{
  border-right: 1px solid white;
 border-left: 1px solid white;
 background-color: lightblue;

}



@keyframes animate{
  40%,60%{
    left:calc(100% + 4px);
  }
  100%{
    left:-13px;
  }
}

/* .animate-dot {
   opacity: 0;
   animation: animateDot1 2s linear infinite;
}

.animate-dot:nth-child(2) {
   animation: animateDot2 2s linear infinite;
}

.animate-dot:nth-child(3) {
   animation: animateDot3 2s linear infinite;
}

@keyframes animateDot1 {
   0%   {opacity: 0; }
   20%  {opacity: 0;}
   30%  {opacity: 1;}
   90% {opacity: 1;}
}

@keyframes animateDot2 {
   0%   {opacity: 0; }
   35%  {opacity: 0;}
   45%  {opacity: 1;}
   90% {opacity: 1;}
}

@keyframes animateDot3 {
   0%   {opacity: 0; }
   50%  {opacity: 0;}
   60%  {opacity: 1;}
   90% {opacity: 1;}
} */
</style>
