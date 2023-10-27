<template>
  <div>
    <div class="main">
      <div class="photo">
        <img src="https://i.postimg.cc/SsRKftR6/wallpaperflare-com-wallpaper.jpg">
        <div class="text">
          <h1>Antonio Tone</h1>
        </div>
      </div>
    </div>
    <div class="row">
    <div class="col-6 text-center head">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem voluptate eius animi odit aliquam corrupti expedita hic cum sit ab optio, esse numquam velit a delectus ratione libero impedit maiores!</div>
    <div class="col-6 text-center sub">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Mollitia eius veritatis pariatur officia aperiam possimus, quod dolorum quibusdam velit, corporis voluptate quis quisquam praesentium porro sit illo tempora quas maiores.</div>
   <div class="about d-flex justify-content-center mb-5">
    <hr class="mx-auto mt-4">
    <button class="btn">About Me</button>
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
.row{
  width:100% !important;
  top: 900px !important;
  padding: 100px;
  

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
  background: black;
  padding: 40px 20px;
  border-radius:999px;
  margin-left: 150px !important;
  /* box-shadow: blue 0px 3px 3px 3px !important; */
bottom: -80% !important;
left: 55%;

}
  
  
</style>