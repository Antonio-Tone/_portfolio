<template>
  <div>
    <div class="qoute mb-5">
      <h1 class="text-center quote mt-5">
      <span
        ><i class="fa-solid fa-quote-left fa-flip-vertical"></i></span
      >Celebrate your unique story, for it is the brushstroke that paints <br />
      the canvas of your remarkable life<span>
        <i class="fa-solid fa-quote-right fa-flip-vertical"></i> </span>
    </h1>
    </div>

    <p class="d-flex justify-content-end w-75 cv">download CV below:</p>
    <div class="d-flex justify-content-center mt-5">
      <hr class="hr">
      <a href="\files\CV of Antonio Tone.pdf" download><magnetic class="switch" buttonText="CV" /></a>
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


</style>
