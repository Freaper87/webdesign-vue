<template>
  <div>
    <Header/>
    <nuxt/>
  </div>
</template>

<style>
* {
	box-sizing: border-box;
}
body,html {
  padding: 0;
  margin: 0;
}
a {
    text-decoration: none;
    color: inherit;
}
.relative {
	position: relative;
}
.absolute {
	position: absolute;
}
</style>

<script>
import Header from '@/components/Header'

export default {
  components: {
    Header
  }
}
</script>