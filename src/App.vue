<template>
  <div id="app">
    <passport title="Hello World!" body="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris vel elit facilisis mi laoreet aliquet ac nec orci. Cras placerat ac urna non iaculis. Cras blandit condimentum volutpat. Quisque vitae commodo urna. Phasellus mollis ante eu sodales maximus. Etiam cursus mollis vehicula. Etiam in neque porttitor, rhoncus magna sit amet, venenatis velit. Vestibulum sodales massa et molestie aliquet. Quisque sit amet est nec metus dictum eleifend. Praesent vestibulum, ex et convallis lacinia, enim leo aliquet ante, non ornare libero dui non neque. Nulla semper nec augue at commodo. Vivamus pharetra mauris nec hendrerit mollis. Morbi libero sem, scelerisque ut ex at, malesuada eleifend eros."></passport>
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
