<script>
import Header from './components/Header.vue'
import Jumbo from './components/Jumbo.vue'
import AppTitle from './components/AppTitle.vue'

export default {
  components: {
    Header,
    Jumbo,
    AppTitle
  }

}
</script>

<template>
  <Header />
  <Jumbo />
  <AppTitle />
</template>

<style scoped>
body {
  width: 100%;
  height: 100%;
  background-color: #222;
}
</style>
