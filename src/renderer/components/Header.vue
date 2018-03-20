<template>
  <div class="m-header">
     <header class="masthead bg-primary pb-5 pt-5 text-white text-center">
      <div class="container">
        <img class="img-fluid mb-5 d-block mx-auto" :src="logo" alt="">
        <h1 class="text-uppercase mb-0">Fast Converter</h1>
        <hr class="star-light">
        <h2 class="font-weight-light mb-0">JSON - CSV - XML - RSS - Dataset</h2>
      </div>
    </header>
  </div>
</template>

<script>
import logo from '../assets/logo.png'

export default {
  name: 'Header',
  data () {
    return {
      logo: logo
    }
  }
}
</script>

<style scoped>

</style>
