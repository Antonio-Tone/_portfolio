<template>
  <div>
    <div class="spacer"></div>
    <div class="box" ref="box"></div>
    <div class="spacer"></div>
    <button @click="scrollToBox">Scroll to Box</button>
  </div>
</template>

<script>
import { gsap } from 'gsap';
import { ScrollTrigger } from 'gsap/ScrollTrigger';
import { ScrollSmoother } from 'gsap/ScrollSmoother';

export default {
  mounted() {
    gsap.registerPlugin(ScrollTrigger, ScrollSmoother);

    const smoother = ScrollSmoother.create({
      smooth: 1,
      effects: true,
      smoothTouch: 0.1,
    });

    gsap.to(this.$refs.box, {
      y: 200,
      scrollTrigger: {
        trigger: this.$refs.box,
        start: 'top center',
        end: 'center center',
        markers: true,
      },
    });
  },
  methods: {
    scrollToBox() {
      gsap.to(window, {
        scrollTo: this.$refs.box,
        duration: 1,
      });
    },
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
