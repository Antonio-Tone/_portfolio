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
          <magnetic class="btn text-center" buttonText="ABOUT" />
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

      <div class="container mb-5 m-0">
        <div class="wrapper">
          <div class="row row-1 mb-3">
            <div class="col-3">
              <div class="flex-col">
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
            <div class="col-3">
              <div class="flex-col">
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
            <div class="col-3">
              <div class="flex-col">
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
            <div class="col-3">
              <div class="flex-col">
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
          <div class="row row-2">
            <div class="col-3">
              <div class="flex-col">
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
            <div class="col-3">
              <div class="flex-col">
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
            <div class="col-3">
              <div class="flex-col">
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
            <div class="col-3">
              <div class="flex-col">
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
      </div>
    </div>
  </div>
</template>
<script>
// import _ from "lodash";
// import Lenis from "@studio-freight/lenis";
import magnetic from "../components/magButtonComp.vue";
export default {
  components: {
    magnetic,
  },
  data() {
    return {
      visibleElement: 1,
      lenis: null,
    };
  },
  mounted() {
     // Create a new Lenis instance
    //  this.lenis = new Lenis();
    // this.lenis.on("scroll", (e) => {
    //   console.log(e);
    // });
    // this.debouncedSmoothScroll = _.debounce(this.smoothScroll, 100);
    // window.addEventListener("scroll", this.debouncedSmoothScroll);
    // this.smoothScroll();

  },
  // beforeDestroy() {
  //   // Remove the event listener when the component is destroyed
  //   window.removeEventListener("scroll", this.debouncedSmoothScroll);
  // },
  methods: {
    show(elementNumber) {
      this.visibleElement = elementNumber;
    },
    //lenis smooth scroll setup
    smoothScroll() {
      // Use the 'lenis' instance created in 'mounted'
      this.lenis.options.duration =0.5;
      this.lenis.options.easing = (t) => Math.min(1, 1.001 - Math.pow(2, -10 * t));

      const raf = (time) => {
        this.lenis.raf(time);
        requestAnimationFrame(raf);
      };

      // function raf(time) {
      //   this.lenis.raf(time);
      //   requestAnimationFrame(raf);
      // }

      requestAnimationFrame(raf);
    },
  },
};
</script>
<style scoped>
.main {
  position: relative;
  min-height: 100vh !important;
}
.header {
  z-index: 0;
  /* border: 5px solid purple !important; */
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
  /* margin-left: 150px !important;  */
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
  height: 90px;
  width: 90px;
  border-radius: 999px;
}
.test {
  font-size: small;
}
.container {
  min-width: 100% !important;
  background-color: lightcoral;
  padding: 23px;
}
.wrapper {
  padding: 20px;
  background-color: greenyellow;
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
.con::after{
  content: "" !important;
}

</style>
