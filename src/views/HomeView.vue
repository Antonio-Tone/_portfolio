<template>
  <div>
    <div class="main">
      <div class="photo">
        <img src="https://i.postimg.cc/SsRKftR6/wallpaperflare-com-wallpaper.jpg" alt="">
        <div class="text">
          <h1>Antonio Tone</h1>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
.main{
  position: relative;
  min-height: 100vh !important;
}
img{
  z-index: 0;
  position: absolute;
min-width: 100% !important;

}
.text{
  z-index: 3;
  position: absolute;
  top: 70%;
  left: 50%;
  transform: translate(-50%,-50%);
}

  
  
</style>