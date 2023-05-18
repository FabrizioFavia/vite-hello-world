<script>
import AppTitle from './components/AppTitle.vue'
import Jumbo from './components/Jumbo.vue'
export default {
components : {
  AppTitle,
  Jumbo
}

}
</script>

<template>
  <AppTitle/>
  <Jumbo/>

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
