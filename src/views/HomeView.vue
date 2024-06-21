<template>
  <div class="boss">
    <!-- hero section -->

    <div class="main">
      <div class="header">
        <div class="skill">
          <h1 class="dev DPP">
            <span>D</span><span>e</span><span>v</span><span>e</span
            ><span>l</span><span>o</span><span>p</span><span>e</span
            ><span>r</span>
          </h1>
          <h1 class="ps DPP">
            <span>P</span><span>r</span><span>o</span><span>b</span
            ><span>l</span><span>e</span><span>m</span><span>&nbsp;</span
            ><span>S</span><span>o</span><span>l</span><span>v</span
            ><span>e</span><span>r</span>
          </h1>
          <h1 class="des DPP">
            <span>D</span><span>e</span><span>s</span><span>i</span
            ><span>g</span><span>n</span><span>e</span><span>r</span>
          </h1>
          <div class="">
            <img
              class="self"
              src="https://i.ibb.co/FWgpbjp/C12-C1-Antonio-Torre-1.jpg"
              alt=""
            />
          </div>
          <div class="location d-flex justify-content-center">
            <img
                        class="pin"
                        src="https://i.ibb.co/4TdQ7rR/output-onlinegiftools-3.gif"
                        alt=""
                      />
            <p class="cape">Northern Suburbs, Cape Town</p>
          </div>
          <div class="Name d-flex justify-content-center">
            <h2 class="AT">Antonio Tone</h2>
            &nbsp;
            <h2 class="AT">-Antonio Tone</h2>
            &nbsp;
            <h2 class="AT">-Antonio Tone</h2>
            &nbsp;
            <h2 class="AT">-Antonio Tone</h2>
            &nbsp;
            <h2 class="AT">-Antonio Tone</h2>
          </div>

        </div>
      </div>
    </div>
    <!--introduction -->

    <div class="row intro">
      <div class="col-6 text-center d-flex justify-content-start intro-1 text_effect">
        <div class="text_overlay"></div>
        <p class="head">Welcome to my digital playground, where pixels meet purpose and
          creativity knows no bounds. Explore the digital tapestry of my work,
          where innovation, design, and passion converge to craft extraordinary
          experiences.</p>
      </div>
      <div class="col-6 text-center d-flex justify-content-center intro-2 text_effect">
        <div class="text_overlay"></div>
        <p class="sub">
          In the world of web design, my passion for design,<br />
          code, and interaction sets me apart and fuels my <br />
          creative edge.
        </p>
      </div>
      <div class="about d-flex justify-content-center mb-5">
        <hr class="mx-auto mt-5" />
        <a href="/about">
          <magnetic class="btn text-center" :buttonText="'About'" />
        </a>
      </div>
    </div>
    <!--projects section -->
    <div class="projects">
      <div class="tst mb-5"><h2>My Work:</h2></div>
      <div class="d-flex justify-content-center">
        <button class="toggle" @click="show(1)">Portfolio</button>
        <button class="toggle" @click="show(2)">E-commerce</button>
        <button class="toggle AS" @click="show(3)">Appliance Store</button>
        <button class="toggle" @click="show(4)">BMI</button>
        <button class="toggle" @click="show(5)">Rental</button>
      </div>
      <div>
        <div class="row prod" v-show="visibleElement === 1">
          <p class="options d-flex justify-content-start"></p>
          <div class="col-6">
            <div class="card">
              <img
                class="img"
                src="https://i.ibb.co/MNxG9bc/Screenshot-2023-10-30-144708.png"
                alt=""
              />
              <div class="textBox">
                <div class="d-flex justify-content-center">
                  <a href="https://lighthearted-marshmallow-2d6528.netlify.app"
                  taget="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/4TdQ7rR/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                  <a href="https://github.com/Antonio-Tone/Profile"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/mHD1Fds/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6 work">
            <div>
              <h2 class="prdName">MY FIRST PORTFOLIO</h2>
                <hr class="prodLine-1">
            </div>
            <p class="text-center disc">
              My very first website, created using HTML, Bootstrap, and CSS.
              This portfolio reflects my early foray into web development,
              showcasing my initial projects, skills, and aspirations. It's a
              simple yet meaningful step in my journey towards mastering web
              development.
            </p>
            <div class="d-flex justify-content-center">
              <ul>
                <il><img class="lang" src="https://i.ibb.co/YyJG396/icons8-bootstrap-48-1.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/SnkmsbK/icons8-css-48.png" alt=""></il>
              </ul>
            </div>
          </div>
        </div>
        <div class="row prod" v-show="visibleElement === 2">
          <p class="options d-flex justify-content-start"></p>

          <div class="col-6">
            <div class="card">
              <img
                class="img"
                src="https://i.ibb.co/zNKTvWN/Screenshot-2023-10-30-150020.png"
                alt=""
              />
              <div class="textBox">
                <div class="d-flex justify-content-center">
                  <a href="https://arsites.netlify.app"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/4TdQ7rR/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                  <a href="https://github.com/Antonio-Tone/e-commerce_pg"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/mHD1Fds/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6 work">
            <h2 class="prdName">MY FIRST E-COMMERCE</h2>
              <hr class="prodLine">
            <p class="text-center disc">
              I used CSS to make it look good, Bootstrap to keep it simple, and
              a bit of JavaScript to add some fun. You can browse properties,
              search with ease, and even click around interactive images. It's a
              bit rough around the edges, but I'm proud of what I've created.
              Give it a go and see if you find your dream place
            </p>
            <div class="d-flex justify-content-center">
              <ul>
                <il><img class="lang" src="https://i.ibb.co/YyJG396/icons8-bootstrap-48-1.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/SnkmsbK/icons8-css-48.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/HqmcxCK/icons8-js-48.png" alt=""></il>
              </ul>
            </div>
          </div>
        </div>
        <div class="row prod" v-show="visibleElement === 3">
          <p class="options d-flex justify-content-start"></p>

          <div class="col-6">
            <div class="card">
              <img
                class="img"
                src="https://i.ibb.co/0cYsDzy/Screenshot-2023-10-30-150857.png"
                alt=""
              />
              <div class="textBox">
                <div class="d-flex justify-content-center">
                  <a href="https://appliance-cartel-node.web.app/"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/4TdQ7rR/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                  <a href="https://github.com/cheslynherman/node-fullstack-eomp"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/mHD1Fds/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6 work">
            <h2 class="prdName">GROUP PROJECT</h2>
              <hr class="prodLine">
            <p class="text-center disc">
              Collaboratively, my classmate and I teamed up to create an
              appliance store webpage using Node.js. This project involved
              designing and implementing a comprehensive online platform for
              customers to browse and purchase appliances. We meticulously
              crafted features such as product listings and an efficient
              checkout system, reflecting our dedication to delivering a
              seamless shopping experience.
            </p>
            <div class="d-flex justify-content-center">
              <ul>
                <il><img class="lang" src="https://i.ibb.co/FB8C8Hr/icons8-api-48.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/94D9cMB/icons8-nodejs-48-1.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/YBm6X1N/icons8-mysql-24.png" alt=""></il>
              </ul>
            </div>

          </div>
        </div>
        <div class="row prod" v-show="visibleElement === 4">
          <p class="options d-flex justify-content-start"></p>
          <div class="col-6">
            <div class="card">
              <img
                class="img"
                src="https://i.ibb.co/mR9f1W9/Screenshot-2023-10-30-151253.png"
                alt=""
              />
              <div class="textBox">
                <div class="d-flex justify-content-center">
                  <a href="https://willowy-druid-f2607c.netlify.app"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/4TdQ7rR/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                  <a href="https://github.com/Antonio-Tone/bmi"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/mHD1Fds/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6 work">
            <h2 class="prdName">My BMI Calculator Journey</h2>
              <hr class="prodLine"> z
            <p class="text-center disc">I had a blast creating a BMI calculator with JavaScript. It showed me that coding is not only fun but also incredibly powerful. I loved being creative, solving problems, and seeing immedia screen andte results. This project was just the beginning, and I'm excited to explore more in the coding world!</p>
            <div class="d-flex justify-content-center">
              <ul>
                <il><img class="lang" src="https://i.ibb.co/YyJG396/icons8-bootstrap-48-1.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/SnkmsbK/icons8-css-48.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/HqmcxCK/icons8-js-48.png" alt=""></il>
              </ul>
            </div>
          </div>
        </div>
        <div class="row prod" v-show="visibleElement === 5">
          <p class="options d-flex justify-content-start"></p>
          <div class="col-6 d-flex justify-content-start">
            <div class="card">
              <img
                class="img"
                src="https://i.ibb.co/Js0XVDf/Screenshot-2023-10-30-151739.png"
                alt=""
              />
              <div class="textBox">
                <div class="d-flex justify-content-center">
                  <a href="https://capstonepj-3a7db.web.app/"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/4TdQ7rR/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                  <a href="https://github.com/Antonio-Tone/capstone_pj"
                  target="_blank"
                    ><button class="toggle linkBg">
                      <img
                        class="links"
                        src="https://i.ibb.co/mHD1Fds/output-onlinegiftools-3.gif"
                        alt=""
                      /></button
                  ></a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-6 work">
            <h2 class="prdName">CAPSTONE</h2>
              <hr class="prodLine">
            <p class="text-center disc5">
              My capstone project was a transformative journey where I designed
              and developed a luxury car rental website using Node.js and
              JavaScript. Throughout the process, I not only created a visually
              stunning and functional website but also discovered valuable
              insights about my strengths and weaknesses. This project allowed
              me to hone my skills in web development, particularly in the
              realms of server-side scripting and client-side interactivity. I
              gained a deep understanding of website architecture, database
              management, and user experience design.
            </p>
            <div class="d-flex justify-content-center">
              <ul>
                <il><img class="lang" src="https://i.ibb.co/HqmcxCK/icons8-js-48.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/FB8C8Hr/icons8-api-48.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/YBm6X1N/icons8-mysql-24.png" alt=""></il>
                <il><img class="lang" src="https://i.ibb.co/94D9cMB/icons8-nodejs-48-1.png" alt=""></il>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- testimonials -->

   <div class="testimonials">
    <div class="tst mb-5"><h2>Endorsements:</h2></div>
    <carousel class="mt-5 mb-5"/>

   </div>
    <!-- contact section -->

    <section class="contact">
      <div class="d-flex justify-content-center heading">
        <img
          class="profile"
          src="https://i.ibb.co/FWgpbjp/C12-C1-Antonio-Torre-1.jpg"
          alt=""
        />
        <h1 class="connect">
          Let's <br /><span class="shift">Connect</span
          ><span class="animate-dot">.</span><span class="animate-dot">.</span>
        </h1>
      </div>
      <div class="d-flex justify-content-center">
        <hr class="hr" />
        <router-link to="/contact"
          ><magnetic class="switch" buttonText="Contact"
        /></router-link>
      </div>
      <div class="d-flex justify-content-center">
        <span class="info">Antoniotone815@gmail.com</span
        ><span class="info">065 851 3653</span>
      </div>
      <div class="row footer">
        <div class="col-6 general">
          <div class="">
            <div><span class="final">Version:</span></div>
            <div class="">2024© Edition</div>
          </div>
        </div>
        <div class="col-6 socials">
          <div class="">
            <div><span class="final">Socials:</span></div>
            <div class="wrapper d-flex justify-content-center p-0">
              <a
                href="https://www.linkedin.com/in/antonio-tone-220925281"
                target="_blank"
                class="link"
                >Linkdin</a
              >
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
import { gsap } from "gsap";
import magnetic from "../components/magButtonComp.vue";
import carousel from "../components/carouselComp.vue";

export default {
  components: {
    magnetic,
    carousel
    },
  data() {
    return {
      tl: gsap.timeline(),
      visibleElement: 1,
      lenis: null,
     
    };
  },
  mounted() {
    this.initialize();
    this.autoType();
    window.addEventListener("scroll", this.handleScroll);
  },

  methods: {
    show(elementNumber) {
      this.visibleElement = elementNumber;
    },
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

    initialize() {
      this.setInitialStates();
      this.header();
      this.createTextAnimation();
    },
    header() {
      const tl = gsap.timeline({
        scrollTrigger: {
          trigger: ".skill",
        },
      });
      tl.to(".skill .dev span", {
        opacity: 1,
        ease: "expo.out",
        stagger: 0.04,
      });
      tl.to(".skill .ps span", {
        opacity: 1,
        ease: "expo.out",
        stagger: 0.04,
      });
      tl.to(".des span", {
        opacity: 1,
        ease: "expo.out",
        stagger: 0.04,
      });
    },
     createTextAnimation(){
      console.log("i am running!")
      this.texts = [...document.querySelectorAll(".text.effect")];

const tl = gsap.timeline({
  scrollTrigger: {
    trigger: ".intro",
    start: "top center",
    end:"bottom top+=10%",
    scrub: true,
    pin:true, 
  }
}

);

    this.texts.forEach((text, index) => {
      const overlay = text.querySelector(".text.overlay");
      const content = text.querySelector(".text_effect p");

      

      tl.to(overlay,{
        scaleX:0
      }).to(content,{
        y:0,
        opacity:1,
        ease:"expo.out",
        duration:2,
        delay:()=> index * 0.1,

      },0)
    })

     },

    setInitialStates() {
      gsap.set(" .dev span", {
        opacity: 0,
      });
      gsap.set(".skill .ps span", {
        opacity: 0,
      });
      gsap.set(".skill .des span", {
        opacity: 0,
      });
    },

   
  },
};
</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@1,300&display=swap');
.main {
  position: relative;
  min-height: 100vh !important;
}
.header {
  width: 100%;
  background: #56ab2f;  /* fallback for old browsers */
background: -webkit-linear-gradient(to right, #a8e063, #56ab2f);  /* Chrome 10-25, Safari 5.1-6 */
background: linear-gradient(to right, #a8e063, #56ab2f); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

  height: 100vh;
  position: relative;
}
.skill {
  height: 100%;
  width: 100%;
  z-index: 0;
  font-family: 'Montserrat', sans-serif;
}
.dev {
  font-size: 100px;
  left: 2%;
  top: 4%;
  position: absolute;
  color: aliceblue;
  font-size: 100px;
}
.ps {
  font-size: 100px;
  top: 4%;
  transform: translateY(180px);
  left: 2%;
  position: absolute;
  /* word-spacing: 120px; */
  color: rgb(28, 29, 32);
}
.des {
  font-size: 100px;

  transform: translateY(340px);
  left: 31%;
  top: 4%;
  position: absolute;
  color: aliceblue;
}

.self {
  object-fit: cover;
  object-position: left top;
  border-radius: 9999px;
  left: 68%;
  top: 8%;
  position: absolute;
  height: 420px;
  width:  420px;
  border: solid 1.5px #fff;


 
}

.Name {
  position: absolute;
  z-index: 25 !important;
  bottom: 2% !important;
  min-width: 100% !important;
  animation-name: infiniteScroll;
  animation-duration: 30s;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}
.AT {
  font-size: 10em;
  display: flex;
  white-space: nowrap !important;

}

@keyframes infiniteScroll {
  from {
    transform: translateX(0);
  }
  to {
    transform: translateX(-50%);
  }
}
.location {
  position: absolute;
  top: 55%;
  left: 1%;
  color: rgb(50, 52, 57);
;
}
.pin {
  height: 35px;
  margin: 6px;
}
.cape{
  font-size: 25px;
}

.scroll {
  transform: translateY(-13px);
}
.intro {
  width: 100% !important;
  top: 900px !important;
  padding: 120px;
}
.head {
  font-size: 1.7em !important;
  display: block !important;
}
.sub {
  font-size: 1.5em;
  display: block !important;
  margin-top: 2em;
  margin-bottom: 1em;
  margin-left: 0;
  margin-right: 0;
 transform: translateY(-20px);
}
.tst{
  position:relative;
  left:8%;
}
.work {
  display: flex;
  flex-direction: column !important;
  align-items: center;
  justify-content: center;
  padding: 1.5em;
  filter: drop-shadow(0px 25px 12px black);
  transform: translateY(-35px);
}
hr {
  position: relative;
  width: 80% !important;
}
.about {
  position: relative;
}
.btn {
  position: absolute;
  z-index: 3;
  bottom: -88% !important;
  left: 48%;
}
.toggle {
  filter: drop-shadow(4px 9px 5px black);

  margin: 5px;
  padding: 5px;
  width: 100px;
  border-radius: 30px;
  color: aliceblue;
  background-color: #80c047;
  border: none !important;
}
.AS {
  font-size: 14px;
}
.toggle:focus {
  background: #6190e8;
  background: -webkit-linear-gradient(to right, #a7bfe8, #6190e8);
  background: linear-gradient(to right, #a7bfe8, #6190e8);
  color: white;
  animation: outerglow 1s alternate infinite cubic-bezier(0.65, 0.05, 0.36, 1);
}

.prdName {
  background-image: radial-gradient(circle at 24.1% 68.8%,#8ACD50 0,#8ACD50 99.4%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent; 
   margin-bottom: 0 !important;
}
.prodLine {
  width: 50% !important;
}
.prodLine-1 {
  width: 100% !important;
}
.lang {
  height: 25px;
  margin-right: 3px;
}
.prod {
  padding: 100px;
}
.options {
  transform: translateX(20px) translateY(-20px);
}
.options::before {
  content: "hover to view" !important;
}
.profile {
  object-fit: cover;
  object-position: left top;
  margin-top: 4px;
  height: 55px;
  width: 55px;
  border-radius: 999px;
  animation: outerglow 1s alternate infinite cubic-bezier(0.65, 0.05, 0.36, 1);
}
@keyframes outerglow {
  0% {
    box-shadow: 0px 0px 0px #1ce278;
  }
  100% {
    box-shadow: 0px 0px 15px #1ce278;
  }
}
.name{
  color:black;
}
.test {
  font-size: small;
  color:white;
}

.container {
  max-width: 100em;
}
.autotype {
  font-size: 14px;
}
.horizontal-single-item {
  height: 210px;
}
.disc {
  font-size: 1.2em;
}

.wrapper {
  padding: 20px;
}
.flex-col {
  background: #232526;
  background: -webkit-linear-gradient(to right, #414345, #232526);
  background: linear-gradient(to right, #414345, #232526);

  padding: 20px;
  height: 250px;
  width: 360px;
  text-align: center !important;
  border-radius: 30px;
}
.links {
  height: 30px;
}
.linkBg {
  background-color: #313131 !important;
  transition:0.5s ease-in-out;
}
.linkBg:hover{
  background-color:#1ce278 !important;
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
}
.row-1 {
  width: 200vw;
  transform: translateX(-2%);
  transition: 1s ease-in-out;
}

.row-2 {
  width: 200vw;
  transform: translateX(-12%);
}

.img {
    filter: drop-shadow(0px 20px 10px black);
  border-radius: 20px;
  width: 600px;
  height: 285px;
  position: absolute;
  transition: 0.2s ease-in-out;
}

.textBox {
  opacity: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 15px;
  transition: 0.2s ease-in-out;
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



.contact {
  background: rgb(28, 29, 32);
  height: 760px;
}
.heading {
  transform: translateX(-350px) translateY(120px);
  font-family: 'Archivo Narrow', sans-serif;
font-family: 'Cormorant', serif;
}
.connect {
  font-size: 5rem;
  margin-left: 10px !important;
}
.heading > .profile {
  height: 75px;
  width: 75px;
  border-radius: 999px;
  transform: translateY(100px) translateX(75px);
}
.shift {
  margin-left: 90px;
  background-image: radial-gradient(circle at 24.1% 68.8%,#6bab32 0,#6bc71b 99.4%);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent; 
}

.hr {
  transform: translateY(200px);
  width: 65% !important;
}
.switch {
  position: relative;
  top:98% ;
  right:250% ;
  /* transform: translateY(145px) translateX(-290px); */
  z-index: 3;
}
.info {
  transform: translateY(160px) translateX(-290px);
  margin-right: 2rem;
  border: 1px solid rgb(219, 188, 188);
  padding: 15px;
  border-radius: 30px;
  transition: 2s ease-in-out;
  color:white;
}
.info:hover {
  background-color: #80c047;
  cursor: pointer !important;
}
.footer {
  transform: translateY(300px) !important;
}
.final{
  color:#80c047;
  -webkit-background-clip: text;
  background-clip: text;
}
.general {
  transform: translateX(150px);
  display: flex;
  flex-direction: column;
  align-items: start;

}
.socials {
  transform: translateX(-150px);
  display: flex;
  flex-direction: column;
  align-items: end;
  justify-content: end;

}
.link {
  text-decoration: none;
  color: white;
  margin-right: 5px;
  transition: 1s ease-in-out;
  padding: 5px;
}

.link:hover {
  border-right: 1px solid white;
  border-left: 1px solid white;
  background-color: #80c047;
}

@keyframes animate {
  40%,
  60% {
    left: calc(100% + 4px);
  }
  100% {
    left: -13px;
  }
}

.animate-dot {
  opacity: 0;
  animation: animateDot1 1s linear infinite;
}
.animate-dot:nth-child(2) {
  animation: animateDot2 1s linear infinite;
}

.animate-dot:nth-child(3) {
  animation: animateDot3 1s linear infinite;
}

@keyframes animateDot1 {
  0% {
    opacity: 0;
  }
  20% {
    opacity: 0;
  }
  30% {
    opacity: 1;
  }
  90% {
    opacity: 1;
  }
}

@keyframes animateDot2 {
  0% {
    opacity: 0;
  }
  35% {
    opacity: 0;
  }
  45% {
    opacity: 1;
  }
  90% {
    opacity: 1;
  }
}

@keyframes animateDot3 {
  0% {
    opacity: 0;
  }
  50% {
    opacity: 0;
  }
  60% {
    opacity: 1;
  }
  90% {
    opacity: 1;
  }
}

/* responsiveness  styling */

/* Styles for extra small devices (phones) */
@media screen and (min-width: 200px) and (max-width: 450px) {
  .DPP{
    font-size:30px;
  }
  .dev {
  left: 2%;
  top: 55%;
  position: absolute;
  color: aliceblue;
}
.ps {
  top: 37%;
  transform: translateY(180px);
  left: 8%;
  position: absolute;
  /* word-spacing: 120px; */
  color: rgb(28, 29, 32);
}
.des {
  transform: translateY(380px);
  left:50%;
  top: 15%;
  position: absolute;
  color: aliceblue;
}
.location {
  position: absolute;
  top: 76%;
  left: 1%;
  color: rgb(50, 52, 57);
;
}
.pin {
  height: 12px;
  margin: 6px;
}
.cape{
  font-size: 9px;
  transform:translateY(5px);
}

.self {
  object-fit: cover;
  object-position: left top;
  border-radius: 9999px;
  left: 9%;
  top:12%;
  position: absolute;
  height: 250px;
  width:  250px;
  border: solid 1.5px #fff;


 
}

.Name {
  position: absolute;
  z-index: 25 !important;
  bottom: 3% !important;
  width: 200% !important;
  animation-name: infiniteScroll;
  animation-duration: 30s;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}
.AT {
  font-size: 2.5em;
  display: flex;
  white-space: nowrap !important;

}

  /* introduction responsiveness */
.intro{
  min-width:100%;
  padding:20px !important;
}
  .intro-1{
    width:60% !important;
  }
  .intro-2{
    width:40%;
  }
  .head {
    font-size: 0.6em !important;
  }
  .intro {
    padding: 60px;
  }
  .sub {
    font-size: 0.4em !important;
    transform:translateY(10px);
  }

  hr {
    width: 120% !important;
  }
  .btn {
    left: 43% !important;
    bottom: -60% !important;
  }

  /* projects responsiveness */

  .toggle {
    margin: 4px;
    padding: 5px;
    width: 69px;
    font-size: 10px;
  }

  .card,
  .img {
    width: 150px !important;
    height: 160px;
  }

  .prod {
    padding: 10px !important;
    margin-top: 10px;
  }
  .options {
    margin-bottom: 1px;
    margin-top: 20px;
    transform: translateX(20px) translateY(-10px);
  }
  .options:before {
    content: "Tap to view" !important;
  }
  .prdName {
    font-size: 1em;
    margin-left: 10px;
    margin-bottom: 2px;
  }
  .disc {
    font-size: 0.4em !important;
    margin-bottom: 2px !important;
  }
  .disc5{
    font-size:6px;
    font-weight: none;
    margin-bottom: 2px;
    margin-top: none;
  }
  .prodLine, .prodLine-1{
    margin-bottom: 3px;
  }
  .lang {
    height: 15px;
    margin-right: 2px;
  }
  ul {
    padding: 0 !important;
  }
  .flex-col {
    padding: 20px;
    height: 205px;
    width: 210px;
  }
  .test {
    font-size: 0.6em;
  }
  .links {
    height: 30px;
  }
  .holder {
    height: 550px;
  }
  .row-1 {
    width: 400vw;
    transform: translateX(-1%);
  }

  .row-2 {
    width: 400vw;
    transform: translateX(-12%);
  }

  /* contact page */

  .connect {
    font-size: 3rem;
  }
  .heading > .profile {
    height: 55px;
    width: 55px;
    transform: translateY(55px) translateX(80px);
  }
  .heading {
    transform: translateX(-40px) translateY(200px);
  }
  .hr {
    transform: translateX(40px) translateY(300px);
    width: 75% !important;
  }
  .switch {
    transform: translateY(165px) translateX(170px);
  }
  .info {
    transform: translateY(300px) translateX(10px);
    margin-right: 1rem;
    border: 1px solid white;
    padding: 7px;
    border-radius: 30px;
    transition: 2s ease-in-out;
    font-size: 0.7em;
  }

  .general {
    transform: translateX(20px) translateY(155px);
    font-size: 0.7em;
  }
  .socials {
    transform: translateX(-20px) translateY(150px);
    font-size: 0.7em;
  }
}

@media screen and (min-width: 500px) and (max-width: 576px) {
  .DPP{
    font-size:35px;
  }
  .dev {
  left: 2%;
  top: 48%;
  position: absolute;
  color: aliceblue;
}
.ps {
  top: 28%;
  transform: translateY(180px);
  left: 8%;
  position: absolute;
  /* word-spacing: 120px; */
  color: rgb(28, 29, 32);
}
.des {
  transform: translateY(380px);
  left:50%;
  top: 4%;
  position: absolute;
  color: aliceblue;
}
.location {
  position: absolute;
  font-size:1px;
  top: 74%;
  left: 5%;
  color: rgb(50, 52, 57);
;
}
.pin {
  height: 20px;
  margin: 6px;
}
.cape{
  font-size: 15px;
}

.self {
  object-fit: cover;
  object-position: left top;
  border-radius: 9999px;
  left: 30%;
  top: 8%;
  position: absolute;
  height: 260px;
  width:  260px;
  border: solid 1.5px #fff;


 
}

.Name {
  position: absolute;
  z-index: 25 !important;
  bottom: 3% !important;
  width: 200% !important;
  animation-name: infiniteScroll;
  animation-duration: 30s;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}
.AT {
  font-size: 3.8em;
  display: flex;
  white-space: nowrap !important;

}
 
 
  /* introduction responsiveness */

  .head {
    font-size: 0.5em !important;
  }
  .sub {
    font-size: 0.4em !important;
    transform:translateY(5px);
  }

  hr {
    width: 140% !important;
  }
  .btn {
    left: 55% !important;
    bottom:-60% !important;
  }

  /* projects responsiveness */

  .toggle {
    margin: 4px;
    padding: 5.5px;
    width: 77px;
    font-size: 11px;
  }

  .card,
  .img {
    width: 200px !important;
    height: 250px;
  }

  .prod {
    padding: 40px !important;
  }
  .prdName {
    font-size: 1.3em;
  }
  .disc {
    font-size: 0.7em !important;
  }
  .flex-col {
    padding: 20px;
    height: 220px;
    width: 300px;
  }
  .links {
    height: 30px;
  }
  .holder {
    height: 700px;
  }
  .row-1 {
    width: 300vw;
    transform: translateX(-1%);
  }

  .row-2 {
    width: 300vw;
    transform: translateX(-12%);
  }
  .test {
  }
  /* contact page */

  .connect {
    font-size: 3.5rem;
    margin-left: px !important;
  }
  .heading > .profile {
    height: 55px;
    width: 55px;
    transform: translateY(60px) translateX(75px);
  }
  .heading {
    transform: translateX(-150px) translateY(200px);
  }
  .hr {
    transform: translateX(20px) translateY(300px);
    width: 75% !important;
  }
  .switch {
    transform: translateY(260px) translateX(-150px);
  }
  .info {
    transform: translateY(260px) translateX(-140px);
    margin-right: 1rem;
    border: 1px solid white;
    padding: 7px;
    border-radius: 30px;
    transition: 2s ease-in-out;
    font-size: 0.7em;
  }

  .general {
    transform: translateX(30px) translateY(100px);
  }
  .socials {
    transform: translateX(-30px) translateY(100px);
  }
}

/* Styles for medium devices ( smaller laptops) */
@media screen and (min-width: 768px) and (max-width: 900px) {
  .DPP{
    font-size:70px;
  }
  .dev {
  left: 2%;
  top: 48%;
  position: absolute;
  color: aliceblue;
}
.ps {
  top: 42%;
  transform: translateY(180px);
  left: 8%;
  position: absolute;
  /* word-spacing: 120px; */
  color: rgb(28, 29, 32);
}
.des {
  transform: translateY(380px);
  left:50%;
  top: 34%;
  position: absolute;
  color: aliceblue;
}
.location {
  position: absolute;
  font-size:1px;
  top: 72%;
  left: 7%;
  color: rgb(50, 52, 57);
;
}
.pin {
  height: 25px;
  margin: 6px;
}
.cape{
  font-size: 22px;
}

.self {
  object-fit: cover;
  object-position: left top;
  border-radius: 9999px;
  left: 22%;
  top: 8%;
  position: absolute;
  height: 420px;
  width:  420px;
  border: solid 1.5px #fff;


 
}

.Name {
  position: absolute;
  z-index: 25 !important;
  bottom: 3% !important;
  width: 200% !important;
  animation-name: infiniteScroll;
  animation-duration: 30s;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}
.AT {
  font-size: 6.5em;
  display: flex;
  white-space: nowrap !important;

}
  .location {
    transform: translateX(-18.5em) !important;
  }
 

  /* introduction responsiveness */

  .head {
    font-size: 1em !important;
  }
  .sub {
    font-size: 0.8em !important;
  }

  hr {
    width: 100% !important;
  }
  .btn {
    left: 63% !important;
  }

  /* projects responsiveness */
  .card,
  .img {
    width: 300px !important;
    height: 255px;
  }

  .prod {
    padding: 40px !important;
  }
  .disc {
    font-size: 1em !important;
  }
  .flex-col {
    padding: 20px;
    height: 260px;
    width: 300px;
  }
  .test{
    font-weight:none !important;
  }
  .disc5{
    font-size:11px;
    font-weight:none !important;
  }
  .disc{
    font-weight:none !important;
  }
  .links {
    height: 30px;
  }
  .holder {
    height: 700px;
  }
  .row-1 {
    width: 250vw;
    transform: translateX(-1%);
  }

  .row-2 {
    width: 250vw;
    transform: translateX(-12%);
  }
  .test {
  }
  /* contact page */

  .connect {
    font-size: 5rem;
    margin-left: px !important;
  }
  .heading {
    transform: translateX(-200px) translateY(120px);
  }
  .hr {
    transform: translateX(20px) translateY(200px);
    width: 75% !important;
  }
  .switch {
    transform: translateY(160px) translateX(-180px);
  }
  .info {
    transform: translateY(160px) translateX(-180px);
    margin-right: 1rem;
    border: 1px solid white;
    padding: 10px;
    border-radius: 30px;
    transition: 2s ease-in-out;
  }

  .general {
    transform: translateX(30px);
  }
  .socials {
    transform: translateX(-30px);
  }
}

/* Styles for large devices (desktops) */
@media screen and (min-width:992px) and (max-width:996px){
  .DPP{
    font-size:60px !important;
  }
  .dev {
  left: 2%;
  top: 18%;
  position: absolute;
  color: aliceblue;
}
.ps {
  top: 12%;
  transform: translateY(180px);
  left: 8%;
  position: absolute;
  /* word-spacing: 120px; */
  color: rgb(28, 29, 32);
}
.des {
  transform: translateY(380px);
  left:40%;
  top:-4%;
  position: absolute;
  color: aliceblue !important;
}
.location {
  position: absolute;
  font-size:1px;
  top: 68%;
  left: 5%;
  color: rgb(50, 52, 57);
;
}
.pin {
  height: 25px;
  margin: 6px;
}
.cape{
  font-size: 22px;
}

.self {
  object-fit: cover;
  object-position: left top;
  border-radius: 9999px;
  left: 60%;
  top: 8%;
  position: absolute;
  height: 330px;
  width:  330px;
  border: solid 1.5px #fff;


 
}

.Name {
  position: absolute;
  z-index: 25 !important;
  bottom: 1% !important;
  width: 200% !important;
  animation-name: infiniteScroll;
  animation-duration: 30s;
  animation-iteration-count: infinite;
  animation-timing-function: linear;
}
.AT {
  font-size: 5em;
  display: flex;
  white-space: nowrap !important;

}
  .location {
    transform: translateX(-18.5em) !important;
  }
 

  /* introduction responsiveness */

  .head {
    font-size: 1.4em !important;
  }
  .sub{
    font-size: 1.2em !important;
  
  }

  hr {
    width: 65% !important;
  }
  .btn {
    left: 68%;
  }

  /* projects responsiveness */
  .card,
  .img {
    width: 400px !important;
    height: 255px;
  }

  .prod {
    padding: 50px !important;
  }
  .disc {
    font-size: 1em !important;
  }
  .flex-col {
    padding: 20px;
    height: 230px;
    width: 340px;
  }
  .links {
    height: 30px;
  }
  .holder {
    height: 700px;
  }
  .row-1 {
    width: 200vw;
    transform: translateX(-1%);
  }

  .row-2 {
    width: 200vw;
    transform: translateX(-12%);
  }
  
  /* contact page */

  .connect {
    font-size: 5rem;
    margin-left: px !important;
  }
  .heading {
    transform: translateX(-270px) translateY(120px);
  }
  .hr {
    transform: translateY(200px);
    width: 75% !important;
  }
  .info {
    transform: translateY(160px) translateX(-250px);
    margin-right: 1rem;
    border: 1px solid white;
    padding: 12px;
    border-radius: 30px;
    transition: 2s ease-in-out;
  }
}

@media screen and (min-width: 1024px) and (max-width: 1200px) {
  .dev {
    transform: translateX(40px) translateY(25px);
  }
  .DPP {
  }

  .ps {
    transform: translateX(130px) translateY(180px);
    word-spacing: 70px;
  }
  .des {
    transform: translateX(720px) translateY(330px);
  }
  .image {
    transform: translateX(22em) translateY(112px);
  }
  .self {
    height: 33.8em;
  }
  .Name {
    transform: translateX(-23em) translateY(-200px);
    height: 10px !important;
  }
  .location {
    transform: translateX(-31em);
  }
  .AT {
    font-size: 4em;
  }

  /* introduction responsiveness */
  .head {
    font-size: 1.3em !important;
  }

  hr {
    width: 65% !important;
  }
  .btn {
    left: 68%;
  }

  /* projects responsiveness */
  .card,
  .img {
    width: 450px !important;
    height: 255px;
  }

  .prod {
    padding: 80px;
  }
  .disc {
    font-size: 1.1em;
  }
}

/* Styles for extra large devices (large desktops/monitors) */
</style>