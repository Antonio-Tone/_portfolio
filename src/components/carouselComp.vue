<template>
  <div class="carousel">
    <a class="carousel-item" href="#one!"
      ><img src="https://i.ibb.co/FWgpbjp/C12-C1-Antonio-Torre-1.jpg"
    /></a>
    <a class="carousel-item" href="#two!"
      ><img src="https://i.ibb.co/FWgpbjp/C12-C1-Antonio-Torre-1.jpg"
    /></a>
    <a class="carousel-item" href="#three!"
      ><img src="https://i.ibb.co/FWgpbjp/C12-C1-Antonio-Torre-1.jpg"
    /></a>
    <a class="carousel-item" href="#four!"
      ><img src="https://i.ibb.co/FWgpbjp/C12-C1-Antonio-Torre-1.jpg"
    /></a>
    <a class="carousel-item" href="#five!"
      ><img src="https://i.ibb.co/FWgpbjp/C12-C1-Antonio-Torre-1.jpg"
    /></a>
  </div>
</template>
<script>
import "materialize-css/dist/css/materialize.min.css";
import "materialize-css/dist/js/materialize.min.js";
$(document).ready(function () {
  $(".carousel").carousel({
    padding: 200,
  });
  autoplay();
  function autoplay() {
    $(".carousel").carousel("next");
    setTimeout(autoplay, 4500);
  }
});
export default {};
</script>
<style></style>
