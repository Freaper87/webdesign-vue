<template>
  <div>
    <div class="wrapper container"></div>
    <Hero />
    <Section1 />
  </div>
</template>
<style>
.w {
    background: url(~static/wave6.svg);
    bottom: 0px;
    background-position: -400px bottom;
}
.w2 {
    background: url(~static/wave6-2.svg);
    bottom: 0px;
    background-position: -400px bottom;
}
.wave {
    height: 70px;
    background-repeat: repeat-x;
    background-size: 100%;
    position: absolute;
    left: 0px;
    right: 0px;
    bottom: -1px;
    width: 100%;
}
.wrapper {
  left: 0;
  right: 0;
  height: 100%;
  position: fixed;
  background: repeating-linear-gradient(90deg, rgba(0, 0, 0, .05), rgba(0, 0, 0, .05) 1px, transparent 1px, transparent 8.3333%);
}
.wrapper:before {
  content: ' ';
  display: block;
  position: absolute;
  right: 0;
  top: 0;
  bottom: 0;
  width: 1px;
  background: rgba(0, 0, 0, .05);
}
</style>
<script>
import Hero from '@/sections/Hero'
import Section1 from '@/sections/Section1'

export default {
  components: {
    Hero,
    Section1
  }
}

</script>
