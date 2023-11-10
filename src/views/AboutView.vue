<template>
  <div>
    <!-- intro quote -->
    <div class="qoute mb-5">
      <h1 class="text-center quote mt-5">
      <span
        ><i class="fa-solid fa-quote-left fa-flip-vertical"></i></span
      >Celebrate your unique story, for it is the brushstroke that paints <br />
      the canvas of your remarkable life<span>
        <i class="fa-solid fa-quote-right fa-flip-vertical"></i> </span>
    </h1>
    </div>
<!-- CV button download -->
 <div>
  <p class="d-flex justify-content-end w-75 cv">download CV below:</p>
    <div class="d-flex justify-content-center mt-5">
      <hr class="hr">
      <a href="\files\CV of Antonio Tone.pdf" download><magnetic class="switch" buttonText="CV" /></a>
 </div>
 </div>
<!-- image with brief discription -->

<div class="container">
  <div class="row mt-5 intro">
  <div class="col-6 first text-center">
    <h1>brief discription</h1>
  </div>
  <div class="col-6 sec">
    <div class="image__overlay">
    <img class="image" src="https://i.postimg.cc/FR6pwSJS/IMG-1478.jpg" alt="">
  </div>
</div>
</div>
      <!-- skills section -->

      <div class="flex-container p-4 w-100">
      <h2 class="mx-auto d-flex justify-content-center my-5 offer capable">
        WHAT I BRING TO THE TABLE...
      </h2>
    
  
  <div class="row mx-auto mt-5 text-center">
    <div class="col-12 col-md-4 intro text-center">
      <div>
        <div>
          <h2 class="lead mb-5">DESIGN</h2>
        </div>
          <div class="animated animate__bounceInLeft mb-5" style="animation-delay: 2s;">
            <i class="fa-solid fa-pen-nib fa-beat-fade" style="color: #8b8e92;"></i>
            </div>
      </div>
      <div>
        <p class="styling my-5">
          As a developer I love designing, my website look modern and I have a
          creative mind.
        </p>
      </div>
    </div>
    <div class="col-12 col-md-4 intro text-center mb-5">
      <div>
        <div>
          <h2 class="mb-5 lead">DEVELOPMENT</h2>
        </div>
        <div class="animated animate__fadeInDownBig" style="animation-delay: 2s;">
          <i class="fa-solid fa-computer fa-beat-fade" style="color: #696c72;"></i>
        </div>
     
      </div>
      <div class="vl">
        <p class="styling my-5">
          I build scalable websites from scratch that fit seamlessly with
          design. My focus is on micro animations, transitions and interaction.
        </p>
      </div>
    </div>

    <div class="col-12 col-md-4 intro text-center">
      <div>
        <h2 class="mb-5 ps-4 lead">HOSTING</h2>
      </div>
      <div class="animated animate__bounceInRight" style="animation-delay: 2s;">
        <i class="fa-solid fa-globe fa-beat-fade" style="color: #75777a;"></i>
      </div>
      <div class="vl">
        <p class="styling my-5 ps-4">
          I host websites on secure domains and have your site running fast and
          efficiently.
        </p>
      </div>
    </div>
</div>
</div>
</div>

  </div>
</template>
<script>
import magnetic from "../components/magButtonComp.vue";
export default {
  components:{
    magnetic 
  },
  mounted(){
    this.initialize();

  },
  methods: {
   initialize(){
    this.setInitialStates();
    this.overlay();

   },
   setInitialStates(){
    gsap.set('.image__overlay img', {
        opacity: 0,
        scale:1.1,
      });
      gsap.set("image__overlay",{

      })
      this.layers = [...document.querySelectorAll("image__overlay")];
      this.images = [...document.querySelectorAll(".image")];
   },
   overlay(){
    
const tl = gsap.timeline({
  scrollTrigger:{
    trigger: ".intro",
    scrub:true,
    end:'center center',
  }
})
this.layers.forEach(layer => {
  tl.to(layer,{
    ease:'linear',
    yPercent:-20
  })
});
this.images.forEach(image => {
  tl.to(image,{
    ease:'linear',
    yPercent:-15,
    scale:1,
    opacity: 0.7,

  })
});

   }
   
  },
};
</script>
<style scoped>
h1 {
  color: white !important;
  font-size: 60px;
}
i {
  font-size: 20px;
  transform: translateY(-15px) !important;
}
.hr{
  position: relative;
  background-color: white !important;
  /* height: 1px; */
  width: 70%;
}
.switch{
  position: absolute;
  transform: translateY(-35px) translateX(-160px);
  z-index: 3;
}
.cv{
transform: translateX(100px);
}

.intro{
margin-top: 10em !important;
}
.first{
  width: 40%;
}
.image{
  width: 100%;
  height:150%;
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  object-fit: cover;
  
}
.image__overlay{
  width: 100%;
  height: 90%;
  padding-top: 50%;
  position: relative;
  background-color: rgba(0, 0, 0, 0.5) !important;
  z-index: 1 ;
  overflow: hidden;
  margin-bottom: 900px;
}
.sec{
  height: 50rem;
}
</style>
