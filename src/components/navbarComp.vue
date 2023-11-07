<template>
    <div>
        <nav class="">
            <ul class="d-flex justify-content-center nav">
                <li class="copyR mx-start">©Code by Antonio Tone</li>   
                <li class="ms-auto"> <router-link to="/" >Home</router-link></li>
                <li> <router-link to="/about" >About</router-link></li>
                <li> <router-link to="/contact" >contact</router-link></li>
            </ul>
        </nav>
    </div>
</template>
<script>
export default {
    mounted(){
        this.autoType();
    },
    methods:{
        autoType() {
      const text = document.querySelector(".copyR");
      const originalText = text.textContent;

      const textLoad = () => {
        let i = 0;
        const intervalId = setInterval(() => {
          text.textContent = originalText.slice(0, i);
          i ++;
          if (i > originalText.length) {
            clearInterval(intervalId);
          }
        }, 200); 
      };
      setTimeout(() => {}, 2000);

      textLoad();
      setInterval(textLoad, 25000);
    },
    }
}

</script>
<style scoped>
nav{
    position:fixed;
    z-index: 5 !important;
    background-color: transparent !important;
    top: 0 !important;
    min-width: 100%;
}
li{
    list-style: none;

}
a{
    text-decoration: none;
    color: white !important;
    margin-right: 10px;
  
}

    
</style>