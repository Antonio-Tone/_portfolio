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

  </div>
</template>
<script>
import magnetic from "../components/magButtonComp.vue";
export default {
  components:{
    magnetic 
  }
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
  height:100%;
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  object-fit: cover;
  
}
.image__overlay{
  width: 100%;
  height: 50%;
  padding-top: 50%;
  position: relative;
  background-color: rgba(0, 0, 0, 0.5) !important;
  z-index: 1 ;
  overflow: hidden;
  margin-bottom: 900px;
}

</style>
