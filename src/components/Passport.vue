<template>

  <article class="message" v-show="isVisible">
    <div class="message-header">
      {{ title }}

      <button type="button" @click="hideModal">X</button>
    </div>

    <div class="message-body">
      {{ body }}
    </div>
  </article>

</template>

<script>
  export default {
    name: 'passport',
    props: [
      'title',
      'body'
    ],
    methods: {
      hideModal () {
        this.isVisible = false
      }
    },
    data () {
      return {
        isVisible: true
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  @import "../styles/app.scss";
</style>
