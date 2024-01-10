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
              src="https://i.postimg.cc/9F2T8wLq/C12-C1-Antonio-Torre-2-min.jpg"
              alt=""
            />
          </div>
          <div class="location d-flex justify-content-center">
            <img
                        class="pin"
                        src="https://i.postimg.cc/W3qHrzWP/output-onlinegiftools.gif"
                        alt=""
                      />
            <p class="cape">Cape Town, South Africa</p>
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
      <div class="col-6 text-center d-flex justify-content-start">
        <div class="head">
          Welcome to my digital playground, where pixels meet purpose and
          creativity knows no bounds. Explore the digital tapestry of my work,
          where innovation, design, and passion converge to craft extraordinary
          experiences.
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
        <a href="/about">
          <magnetic class="btn text-center" :buttonText="'About'" />
        </a>
      </div>
    </div>
    <!--projects section -->
    <carousel />

    <!-- testimonials -->

    <section class="holder mx-auto">
      <div class="horizontal_item container">
        <div class="row row-1">
          <div class="flex-col">
            <div class="horizontal-single-item">
              <div class="d-flex justify-content-center">
                <img
                  class="profile"
                  src="https://i.postimg.cc/PfcVqj5K/Screenshot-2023-11-08-130937.png"
                  alt="picture"
                />
              </div>
              <div class="text-center">
                <p class="name mx-auto">Tara Snell</p>
                <p class="test autotype">
                  "Antonio is one determined ,dedicated team member to have on
                  any team, he gets the job done and always to lend a hand to
                  make sure the whole team are on the same page."
                </p>
              </div>
            </div>
          </div>
          <div class="flex-col">
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
                  "Antonio is a very fun person to work with and has a great
                  sense of humour.He Is hardworking and disciplined.He could be
                  a role model for many."
                </p>
              </div>
            </div>
          </div>
          <div class="flex-col">
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
                  "He may be a man of few words, but Antonio's hard work and
                  dedication always shine through in whatever he does. You can
                  easily tell he appreciates every opportunity he is given and
                  takes nothing for granted."
                </p>
              </div>
            </div>
          </div>
          <div class="flex-col">
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
                  "Antonio is very independent. Whenever he struggles with
                  something he would rather first try and figure it out himself
                  before asking for help. He is extremely kind and friendly and
                  turns every person he meets for the first time into his
                  friend."
                </p>
              </div>
            </div>
          </div>
          <div class="flex-col">
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
                  "I am thrilled to share my positive testimonial about my
                  experience with Antonio. From the moment I first met him I was
                  impressed. His dedication to excellence and drive to achieve
                  was evident in every interaction I had with him."
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
                  " Antonio is a very hardworking individual.He has improved a
                  lot in both his coding aswell as in his problem solving
                  skills. He is an extremely nice person to work with as he is
                  very friendly"
                </p>
              </div>
            </div>
          </div>
          <div class="flex-col m-2">
            <div class="horizontal-single-item">
              <div class="d-flex justify-content-center">
                <img
                  class="profile"
                  src="https://i.postimg.cc/d0K2cczD/C12-Ayesha-Galant-Class1-1.jpg"
                  alt="picture"
                />
              </div>
              <div class="text-center">
                <p class="name mx-auto">Ayesha Galant</p>
                <p class="test autotype">
                  "Working alongside Antonio on several IT ventures has been an
                  absolute pleasure. His precision-oriented approach coupled
                  with his knack for troubleshooting is highly commendable. He
                  unequivocally embodies talent and commitment in his work
                  ethic."
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
                  "Antonio is an exceptionally hard worker and always making
                  time to assist anyone who is in need. Also goes the extra-mile
                  when doing anything that has to be done. He is also very
                  confident in his capabilities and never fails to get the Job
                  done"
                </p>
              </div>
            </div>
          </div>
          <div class="flex-col m-2">
            <div class="horizontal-single-item">
              <div class="d-flex justify-content-center">
                <img
                  class="profile"
                  src="https://i.postimg.cc/rpZQXwLc/C12-Laiquah-Cotie-2.jpg"
                  alt="picture"
                />
              </div>
              <div class="text-center">
                <p class="name mx-auto">Laiquah Cotie</p>
                <p class="test autotype">
                  "Antonio is an exceptional professional, with deep expertise,
                  dedication, and strong problem-solving skills. His work ethic,
                  clear communication, and collaborative nature make him a
                  remarkable team player. I wholeheartedly recommend him."
                </p>
              </div>
            </div>
          </div>
          <div class="flex-col m-2">
            <div class="horizontal-single-item">
              <div class="d-flex justify-content-center">
                <img
                  class="profile"
                  src="https://i.postimg.cc/3R6GxMds/Screenshot-2023-10-04-154441.png"
                  alt="picture"
                />
              </div>
              <div class="text-center">
                <p class="name mx-auto">Ganiefah Majiet</p>
                <p class="test autotype">
                  "Antonio one, someone who Id definitely recommend. His always
                  positive and willing to help the next person although he
                  himself is busy, his an intelligent and very hardworking
                  person. He is always positive and he always provides everyone
                  with help and motivation"
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
        <img
          class="profile"
          src="https://i.postimg.cc/y6cxh6tZ/T02-LW4-RMXJQ-U051-ZHJ00-N9-edefadf5b7cb-512.png"
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
            <div class=""><span>Version:</span></div>
            <div class="">2023© Edition</div>
          </div>
        </div>
        <div class="col-6 socials">
          <div class="">
            <div class=""><span>Socials:</span></div>
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
import Carousel from "../components/carouselComp.vue";
export default {
  components: {
    magnetic,
    Carousel,
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

    handleScroll() {
      const container = this.$el.querySelector(".holder");
      const row2 = this.$el.querySelector(".row-1");
      const itemsRow1 = document.querySelectorAll(".row-1 .flex-col");
      const itemsRow2 = document.querySelectorAll(".row-2 .flex-col");
      const cardMargin = 200; // Adjust this value based on your actual card margin
      const totalWidth =
        (itemsRow1.length + itemsRow2.length) * (500 + cardMargin);

      // Get the scroll position
      const scrollPosition = window.scrollY;

      // Define the trigger positions for your animations
      const triggerPositionRow1 = container.offsetTop - window.innerHeight / 2;
      const triggerPositionRow2 = row2.offsetTop - window.innerHeight / 2;

      // Check if the scroll position has reached the trigger position for Row 1
      if (scrollPosition > triggerPositionRow1) {
        itemsRow1.forEach((item, index) => {
          const offset = (index - itemsRow1.length / 2) * (-650 + cardMargin);
          const progress =
            (scrollPosition - triggerPositionRow1 - offset) / totalWidth;
          item.style.transform = `translateX(${progress * 200}%)`;
        });
      }

      // Check if the scroll position has reached the trigger position for Row 2
      if (scrollPosition > triggerPositionRow2) {
        itemsRow2.forEach((item, index) => {
          const offset = (index + 1) * 300;
          const progress =
            (scrollPosition - triggerPositionRow2 - offset) / totalWidth;
          item.style.transform = `translateX(${progress * -200}%)`;
        });
      }
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
  font-size: 10rem;
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
  font-size: 12em;
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
  /* transform: translateX(-40em) translateY(450px); */
  position: absolute;
  top: 55%;
  left: 3%;
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
  font-size: 2em !important;
  display: block !important;
}
.sub {
  font-size: 1.6em;
  display: block !important;
  margin-top: 2em;
  margin-bottom: 1em;
  margin-left: 0;
  margin-right: 0;
 transform: translateY(-20px);
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

  transition: 1s ease-in-out;
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
  color: rgb(16, 16, 16) !important;
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
  margin-top: 4px;
  height: 45px;
  width: 45px;
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

.test {
  font-size: small;
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
  border-radius: 20px;
  width: 600px;
  height: 285px;
  position: absolute;
  transition: 0.2s ease-in-out;
  /* z-index: 1; */
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

/* .card:hover {
  transform: scale(1.09);
} */

.contact {
  background: rgb(28, 29, 32);
  height: 760px;
}
.heading {
  transform: translateX(-350px) translateY(120px);
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
}

.hr {
  transform: translateY(200px);
  width: 65% !important;
}
.switch {
  transform: translateY(160px) translateX(-290px);
  z-index: 3;
}
.info {
  transform: translateY(160px) translateX(-290px);
  margin-right: 2rem;
  border: 1px solid white;
  padding: 15px;
  border-radius: 30px;
  transition: 2s ease-in-out;
}
.info:hover {
  background-color: #14ae5c;
  cursor: pointer !important;
}
.footer {
  transform: translateY(300px) !important;
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
  background-color: lightblue;
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
@media screen and (min-width: 300px) and (max-width: 450px) {
  .self {
    height: 22em !important;
    width: 10em;
  }
  .image {
    transform: translateX(2em) translateY(300px) !important;
  }
  .dev {
    transform: translateX(10px) translateY(88px);
  }
  .DPP {
    font-size: 2.5em !important;
  }

  .ps {
    transform: translateX(28px) translateY(190px) !important;
    word-spacing: 10px;
  }
  .des {
    transform: translateX(170px) translateY(300px) !important;
  }
  .Name {
    transform: translateX(-1em) translateY(-163px) !important;
  }
  .location {
    transform: translateX(4.5em) translateY(25px) !important;
  }
  .location > p {
    font-size: 0.6em !important;
  }
  .fa-fade {
    transform: translateY(-3px);
    font-size: 0.5em !important;
  }
  .AT {
    font-size: 2em;
  }

  /* introduction responsiveness */

  .head {
    font-size: 0.3em !important;
  }
  .intro {
    padding: 60px;
  }
  .sub {
    font-size: 0.2em !important;
  }

  hr {
    width: 120% !important;
  }
  .btn {
    left: 43% !important;
    bottom: -40% !important;
  }

  /* projects responsiveness */

  .toggle {
    margin: 3px;
    padding: 7px;
    width: 52px;
    font-size: 8.5px;
  }

  .card,
  .img {
    width: 150px !important;
    height: 150px;
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
    content: "Tab to view" !important;
  }
  .prdName {
    font-size: 1.2em;
    margin-left: 10px;
  }
  .disc {
    font-size: 0.4em !important;
    margin-bottom: 2px !important;
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
    font-size: 2.5rem;
    margin-left: px !important;
  }
  .heading > .profile {
    height: 55px;
    width: 55px;
    transform: translateY(45px) translateX(80px);
  }
  .heading {
    transform: translateX(-40px) translateY(200px);
  }
  .hr {
    transform: translateX(40px) translateY(300px);
    width: 75% !important;
  }
  .switch {
    transform: translateY(275px) translateX(-105px);
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
    transform: translateX(20px) translateY(180px);
    font-size: 0.5em;
  }
  .socials {
    transform: translateX(-20px) translateY(180px);
    font-size: 0.5em;
  }
}

@media screen and (min-width: 500px) and (max-width: 576px) {
  .self {
    height: 29em;
    width: 12em;
  }
  .image {
    transform: translateX(10em) translateY(188px) !important;
  }
  .dev {
    transform: translateX(10px) translateY(28px);
  }
  .DPP {
    font-size: 4.5em !important;
  }

  .ps {
    transform: translateX(40px) translateY(200px) !important;
    word-spacing: 60px;
  }
  .des {
    transform: translateX(325px) translateY(370px) !important;
  }
  .Name {
    transform: translateX(-11em) translateY(-180px) !important;
  }
  .location {
    transform: translateX(-11em) !important;
  }
  .AT {
    font-size: 3em;
  }

  /* introduction responsiveness */

  .head {
    font-size: 0.6em !important;
  }
  .sub {
    font-size: 0.4em !important;
  }

  hr {
    width: 140% !important;
  }
  .btn {
    left: 50% !important;
  }

  /* projects responsiveness */

  .toggle {
    margin: 5px;
    padding: 3px;
    width: 50px;
    font-size: 8px;
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
    transform: translateY(220px) translateX(-140px);
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
@media screen and (min-width: 768px) and (max-width: 768px) {
  .self {
    height: 32em !important;
  }
  .image {
    transform: translateX(11em) translateY(140px) !important;
  }
  .dev {
    transform: translateX(40px) translateY(28px);
  }
  .DPP {
    font-size: 5.5em !important;
  }

  .ps {
    transform: translateX(60px) translateY(190px) !important;
    word-spacing: 90px;
  }
  .des {
    transform: translateX(500px) translateY(370px) !important;
  }
  .Name {
    transform: translateX(-11em) translateY(-200px) !important;
    height: 10px !important;
  }
  .location {
    transform: translateX(-18.5em) !important;
  }
  .AT {
    font-size: 4em;
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
    height: 230px;
    width: 300px;
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
@media screen and (min-width: 992px) and (max-width: 1023.98px) {
  .self {
    height: 31.8em !important;
  }
  .image {
    transform: translateX(18em) translateY(144px) !important;
  }
  .dev {
    transform: translateX(40px) translateY(25px);
  }
  .DPP {
    font-size: 7.7em !important;
  }

  .ps {
    transform: translateX(80px) translateY(180px) !important;
    word-spacing: 70px;
  }
  .des {
    transform: translateX(615px) translateY(330px) !important;
  }
  .Name {
    transform: translateX(-18em) translateY(-200px) !important;
    height: 10px !important;
  }
  .location {
    transform: translateX(-25.5em) !important;
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
  .test {
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
    font-size: 8.2em;
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
