<template>
  <div class="container">
    <titlebar />
    <nuxt />
  </div>
</template>

<script>
import titlebar from '~/components/titlebar.vue'

export default {
  components: {
    titlebar
  }
}
</script>

<style>
html {
  font-family: monospace;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: hsl(0, 0%, 4%);
  color: hsl(0, 0%, 96%);
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

a {
  color: #fff;
  transition: all 0.5s ease 0s;
}

a:hover {
  color: #eee;
  opacity: 0.7;
  transition: all 0.5s ease 0s;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
