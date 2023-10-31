<!-- <template>
  <div>
    <div class="scroll-wrapper">
      <div class="main">
      <div class="photo">
        <img class="header" src="https://i.postimg.cc/SsRKftR6/wallpaperflare-com-wallpaper.jpg">
        <div class="text">
          <h1>Antonio Tone</h1>
        </div>
      </div>
    </div>
    <div class=" row intro">
    <div class="col-6 text-center head">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem voluptate eius animi odit aliquam corrupti expedita hic cum sit ab optio, esse numquam velit a delectus ratione libero impedit maiores!</div>
    <div class="col-6 text-center sub">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Mollitia eius veritatis pariatur officia aperiam possimus, quod dolorum quibusdam velit, corporis voluptate quis quisquam praesentium porro sit illo tempora quas maiores.</div>
   <div class="about d-flex justify-content-center mb-5">
    <hr class="mx-auto mt-5">
    <magnetic class="btn text-center"/>
   </div>
    </div>
    <button @click="show(1)">1</button>
    <button @click="show(2)">2</button>
    <button @click="show(3)">3</button>
    <button @click="show(4)">4</button>
    <button @click="show(5)">5</button>
    <div class="row prod" v-show="visibleElement === 1">
      <div class="col-6">
        <img class="image" src="https://i.postimg.cc/SsRKftR6/wallpaperflare-com-wallpaper.jpg">
      </div>
      <div class="col-6">
        <p class="head text-center mt-5">
          1
        </p>
      </div>
    </div>
     <div class="row prod" v-show="visibleElement === 2">
       <div class="col-6 d-flex justify-content-start">
         <img class="image" src="https://i.postimg.cc/SsRKftR6/wallpaperflare-com-wallpaper.jpg">
       </div>
      <div class="col-6">
        <p class="head text-center d-flex justify-content-center mt-5">
          2
        </p>
      </div>
    </div> 
    <div class="row prod" v-show="visibleElement === 3">
      <div class="col-6">
        <img class="image" src="https://i.postimg.cc/SsRKftR6/wallpaperflare-com-wallpaper.jpg">
      </div>
      <div class="col-6">
        <p class="head text-center mt-5">
         3
        </p>
      </div>
    </div>
    <div class="row prod" v-show="visibleElement === 4">
      <div class="col-6">
        <img class="image" src="https://i.postimg.cc/SsRKftR6/wallpaperflare-com-wallpaper.jpg">
      </div>
      <div class="col-6">
        <p class="head text-center mt-5">
          4
        </p>
      </div>
    </div>
    <div class="row prod" v-show="visibleElement === 5">
      <div class="col-6 d-flex justify-content-start">
        <img class="image" src="https://i.postimg.cc/SsRKftR6/wallpaperflare-com-wallpaper.jpg">
      </div>
      <div class="col-6">
        <p class="head text-center mt-5">
          5
        </p>
      </div>
     </div>
    
     <div class="container mb-5 m-0">
    <div class="wrapper">
      <div class="row row-1 mb-3">
        <div class="col-3">
           <div class="flex-col">
            <div class="d-flex justify-content-center">
            <img class="profile" src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg" alt="picture">
           </div>
           <div class="text-center">
            <p class="test">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eveniet reiciendis et facilis fugit repellat! Voluptatibus, dignissimos tempore dolorum ipsam deleniti optio mollitia minima aspernatur porro quis error sit veniam unde?</p>
           </div>
           </div>
        </div>
        <div class="col-3">
          <div class="flex-col">
            <div class="d-flex justify-content-center">
            <img class="profile" src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg" alt="picture">
           </div>
           <div class="text-center">
            <p class="test">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eveniet reiciendis et facilis fugit repellat! Voluptatibus, dignissimos tempore dolorum ipsam deleniti optio mollitia minima aspernatur porro quis error sit veniam unde?</p>
           </div>
          </div>
        </div>
        <div class="col-3">
          <div class="flex-col">
            <div class="d-flex justify-content-center">
            <img class="profile" src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg" alt="picture">
           </div>
           <div class="text-center">
            <p class="test">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eveniet reiciendis et facilis fugit repellat! Voluptatibus, dignissimos tempore dolorum ipsam deleniti optio mollitia minima aspernatur porro quis error sit veniam unde?</p>
           </div>
          </div>
        </div>
        <div class="col-3">
          <div class="flex-col">
            <div class="d-flex justify-content-center">
            <img class="profile" src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg" alt="picture">
           </div>
           <div class="text-center">
            <p class="test">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eveniet reiciendis et facilis fugit repellat! Voluptatibus, dignissimos tempore dolorum ipsam deleniti optio mollitia minima aspernatur porro quis error sit veniam unde?</p>
           </div>
          </div>
        </div>

      </div>
      <div class="row row-2">
        <div class="col-3">
          <div class="flex-col">
            <div class="d-flex justify-content-center">
            <img class="profile" src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg" alt="picture">
           </div>
           <div class="text-center">
            <p class="test">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eveniet reiciendis et facilis fugit repellat! Voluptatibus, dignissimos tempore dolorum ipsam deleniti optio mollitia minima aspernatur porro quis error sit veniam unde?</p>
           </div>
          </div>
        </div>
        <div class="col-3">
          <div class="flex-col">
            <div class="d-flex justify-content-center">
            <img class="profile" src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg" alt="picture">
           </div>
           <div class="text-center">
            <p class="test">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eveniet reiciendis et facilis fugit repellat! Voluptatibus, dignissimos tempore dolorum ipsam deleniti optio mollitia minima aspernatur porro quis error sit veniam unde?</p>
           </div>
          </div>
        </div>
        <div class="col-3">
          <div class="flex-col">
            <div class="d-flex justify-content-center">
            <img class="profile" src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg" alt="picture">
           </div>
           <div class="text-center">
            <p class="test">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eveniet reiciendis et facilis fugit repellat! Voluptatibus, dignissimos tempore dolorum ipsam deleniti optio mollitia minima aspernatur porro quis error sit veniam unde?</p>
           </div>
          </div>
        </div>
        <div class="col-3">
          <div class="flex-col">
            <div class="d-flex justify-content-center">
            <img class="profile" src="https://i.postimg.cc/XqFnBDX2/IMG-1478-1.jpg" alt="picture">
           </div>
           <div class="text-center">
            <p class="test">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eveniet reiciendis et facilis fugit repellat! Voluptatibus, dignissimos tempore dolorum ipsam deleniti optio mollitia minima aspernatur porro quis error sit veniam unde?</p>
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
import Lenis from '@studio-freight/lenis'
import { gsap } from 'gsap';
import { ScrollTrigger } from 'gsap/ScrollTrigger';
import { ScrollSmoother } from 'gsap/ScrollSmoother';
import magnetic from "../components/magButtonComp.vue"
export default {
  components: {
    magnetic
  },
  data() {
    return {
      visibleElement: 1,
      Lenis:null,
    };
  },
  mounted() {
    gsap.registerPlugin(ScrollTrigger, ScrollSmoother);
       // Create the ScrollSmoother instance
       const smoother = ScrollSmoother.create({
      smooth: 1, // how long (in seconds) it takes to "catch up" to the native scroll position
      effects: true, // looks for data-speed and data-lag attributes on elements
      smoothTouch: 0.1, // much shorter smoothing time on touch devices (default is NO smoothing on touch devices)
    });

    // Create a ScrollTrigger animation
    gsap.to(this.$refs.box, {
      y: 200,
      scrollTrigger: {
        trigger: "scroll-wrapper",
        start: 'top center',
        end: 'center center',
        markers: true, // For debugging, you can remove this in production
      },
    });
  },
};
</script>

<style scoped>
.spacer {
  height: 500px;
}

.box {
  width: 100px;
  height: 100px;
  background-color: #3498db;
}
</style>
Save to grepper
In this example, we've created a simple Vue component that uses GSAP to create a smooth scrolling effect on the "box" element. We import GSAP plugins, register them, and create a ScrollSmoother instance. The "box" element will animate when it enters the viewport.

Make sure to adjust the elements and animations to fit your specific use case.




Is this conversation helpful so far?




  },
  methods: {
    show(elementNumber) {
      this.visibleElement = elementNumber;
    },
    show(elementNumber) {
      this.visibleElement = elementNumber;
    },
    smoothScroll() {
      const lenis = this.lenis;

      function raf(time) {
        lenis.raf(time);
        requestAnimationFrame(raf);
      }

      requestAnimationFrame(raf);
    },
  },
  
};

</script>
<style scoped>
.main{
  position: relative;
  min-height: 100vh !important;
}
.header{
  z-index: 0;
  /* border: 5px solid purple !important; */
  position: absolute;
min-width: 100% !important;
height: 100% !important;

}
.text{
  z-index: 3;
  position: absolute;
  top: 70%;
  left: 50%;
  transform: translate(-50%,-50%);
}
.intro{
  width:100% !important;
  top: 900px !important;
  padding: 120px;
  

}
.head{
  font-size: larger !important;
}
.sub{
  font-size: small;
}
hr{
  position: relative;
  width: 50% !important;
}
.about{
  position: relative;
}
.btn{
  position: absolute;
  z-index: 3;
/* margin-left: 150px !important;  */
bottom: -60% !important;
left: 60%;

}
.prod{
  padding: 100px;
}
.image{
  height: 250px;
  width: 450px;
  /* left: 50%; */
  /* transform: translate(50%,-50%);} */
  
}
.profile{
  height: 90px;
  width: 90px;
  border-radius:999px
}
.test{
  font-size: small;
}
.container{
  min-width: 100% !important;
  background-color: lightcoral;
  padding: 23px;
}
.wrapper{
  padding: 20px;
background-color: greenyellow;
}
.flex-col{
  background-color: burlywood;
  padding: 20px;
 height: 250px;
 width: 300px;
}
.col-4{
  /* background-color: grey; */
 
}

</style> -->