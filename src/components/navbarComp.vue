<template>
    <div>
        <nav>
            <ul class="d-flex justify-content-center nav">
                <li class="copyR mx-start">©Code by Antonio Tone</li>   
                <li class="ms-auto"> <router-link class=" link" to="/" >Home</router-link></li>
                <li> <a class="link" href="/about" >About</a></li>
                <li> <router-link class="link" to="/contact" >Contact</router-link></li>
            </ul>
        </nav>
    </div>
</template>
<script>
export default {
    mounted(){
        this.autoType();
        this.initializeHoverEffect();
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
    initializeHoverEffect(){
            var hoverMouse = function ($el) {
  $el.each(function () {
    var $self = $(this);
    var hover = false;
    var offsetHoverMax = $self.attr("offset-hover-max") || 0.7;
    var offsetHoverMin = $self.attr("offset-hover-min") || 0.5;

    var attachEventsListener = function () {
      $(window).on("mousemove", function (e) {
        //
        var hoverArea = hover ? offsetHoverMax : offsetHoverMin;

        // cursor
        var cursor = {
          x: e.clientX,
          y: e.pageY
        };

        // size
        var width = $self.outerWidth();
        var height = $self.outerHeight();

        // position
        var offset = $self.offset();
        var elPos = {
          x: offset.left + width / 2,
          y: offset.top + height / 2
        };

        // comparaison
        var x = cursor.x - elPos.x;
        var y = cursor.y - elPos.y;

        // dist
        var dist = Math.sqrt(x * x + y * y);

        // mutex hover
        var mutHover = false;

        // anim
        if (dist < width * hoverArea) {
          mutHover = true;
          if (!hover) {
            hover = true;
          }
          onHover(x, y);
        }

        // reset
        if (!mutHover && hover) {
          onLeave();
          hover = false;
        }
      });
    };

    var onHover = function (x, y) {
      TweenMax.to($self, 0.4, {
        x: x * 0.3,
        y: y * 0.4,
        //scale: .9,
        rotation: x * 0.05,
        ease: Power2.easeOut
      });
    };
    var onLeave = function () {
      TweenMax.to($self, 0.7, {
        x: 0,
        y: 0,
        scale: 1,
        rotation: 0,
        ease: Elastic.easeOut.config(1.2, 0.4)
      });
    };

    attachEventsListener();
  });
};

hoverMouse($("li"));
        }
    }
}

</script>
<style scoped>
nav{
    position:fixed;
    z-index: 999 !important;
    background-color: transparent !important;
    border-bottom:none !important;
    top: 0 !important;
    min-width: 100%;
}
li{
    list-style: none;
    font-size: 17px;
    padding: 5px;
    /* transition: 1s ease-in-out; */

}
a{
    text-decoration: none;
    color:white;
    margin-right: 10px;
  
}
ul{
    margin-top: 3px;
}
.link{
  transition: 0.5s;
}

.link:focus{
  border-block: 1px solid #4e851e;
}

@media screen and (min-width: 300px) and (max-width:380px){
  .copyR{
    display: none !important;
  }
}

    
</style>