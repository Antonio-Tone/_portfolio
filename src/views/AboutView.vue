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

    <div class="d-flex justify-content-center">
      <hr class="hr">
      <a href="/contact"><magnetic class="switch" buttonText="Contact" /></a>
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
<style>
h1 {
  color: white !important  ;
}
i {
  font-size: 20px;
  transform: translateY(-15px) !important;
}
.hr{
  position: relative;
  background-color: white !important;
  /* height: 1px; */
  width: 50%;
}
.switch{
  position: absolute;
  transform: translateY(-35px) translateX(-130px);
  z-index: 3;
}


</style>
