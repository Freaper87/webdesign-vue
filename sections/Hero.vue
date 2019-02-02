<template>
    <section class="hero is-fullheight">
      <div class="hero-body blue">    
          <div class="w wave"></div>
          <div class="geometry">
            <svg class="hero-rectangle">
              <rect class="rhombus" x="-50%" y="-50%" width="100%" height="100%" transform="rotate(45)" fill="#fff" fill-opacity="0.05"></rect>
            </svg>
            <svg class="absolute hero-circle">
              <circle cx="50%" cy="50%" r="50%" fill="#fff" fill-opacity="0.05"></circle>
            </svg>
            <svg class="absolute hero-circle2">
              <circle cx="50%" cy="50%" r="50%" fill="#fff" fill-opacity="0.05"></circle>
            </svg>
          </div>
          <div class="container">
            <h1 class="is-size-1 has-text-white title has-text-weight-bold is-lowercase">professionelles Webdesign</h1>
            <div class="custom-hr column is-3 is-paddingless">
              <span></span><div class="diamond"></div><span></span>
            </div>
            <h2 class="has-text-white subtitle has-text-weight-light is-family-secondary">Hinterlasse einen bleibenden Eindruck<br> mit einer modernen und<br>individuellen Webseite!</h2>
            <button class="button">Button</button>
          </div>
        </div>

        <div class="w wave"></div>
    </section>
</template>
<style>
.blue {
  background-color: #5b53ff;
  background: rgb(103, 69, 194);
  background: linear-gradient(to bottom, rgba(103, 69, 194, 1) 0%, rgba(91, 83, 255, 1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#6745c2', endColorstr='#5b53ff', GradientType=0);
  overflow: hidden;
}
figure {
  margin: 0;
}

.geometry {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  background: 0 0;
  overflow: hidden;
}

.hero-rectangle {
  left: 0%;
  width: 50vw;
  height: 50vw;
  top: -0%;
}

.hero-circle {
  width: 35vw;
  height: 35vw;
  right: -10%;
  top: 20%;
}

.hero-circle2 {
  width: 25vw;
  height: 25vw;
  right: 15%;
  top: 40%;
}

.custom-hr {
  display: inline-block;
  margin-bottom: 1.5rem;
}

.custom-hr span {
  width: calc(50% - 14px);
  float: left;
  margin: 6px 0px 0px 0px;
  display: inline-block;
  border-bottom: 1px solid rgba(255, 255, 255, .75);
}

.custom-hr div {
  display: inline-block;
}

.diamond {
  width: 0;
  height: 0;
  float: left;
  border: 8px solid transparent;
  border-bottom-color: #fff;
  position: relative;
  top: -9px;
  margin: 0px 6px 0px 6px;
}

.diamond:after {
  content: '';
  position: absolute;
  left: -8px;
  top: 8px;
  width: 0;
  height: 0;
  border: 8px solid transparent;
  border-top-color: #fff;
}
</style>
<script>
export default {
  name: 'Hero'
}

</script>
