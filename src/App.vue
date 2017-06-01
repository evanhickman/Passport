<template>
  <div id="app">
    <passport></passport>
  </div>
</template>

<script>
import Passport from './components/Passport'

export default {
  name: 'app',
  components: {
    Passport
  }
}
</script>

<style>
  @import "./styles/app.scss";
</style>
