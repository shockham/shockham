<template>
  <div class="header">
    <div class="titlebar">
      <logo />
      <h1 class="title">
        SHOCKHAM
      </h1>
    </div>
    <div class="links">
      social:
      <a
        href="https://twitter.com/shockham"
        target="_blank"
      >twitter</a>
      <a
        href="https://github.com/shockham"
        target="_blank"
      >github</a>
      <a
        href="https://shockham.bandcamp.com/"
        target="_blank"
      >bandcamp</a>
    </div>
    <div>
      nav:
      <n-link
        to="/"
      >home</n-link>
      <n-link
        to="/games"
      >games</n-link>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.title {
  flex: auto;
  font-weight: 300;
  font-size: 100px;
  color: hsl(0, 0%, 100%);
  letter-spacing: 1px;
}

.links {
  border-top: 1px #fff solid;
}

.header {
  border-bottom: 1px #fff solid;
}
</style>
