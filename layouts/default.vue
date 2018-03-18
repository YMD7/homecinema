<template lang="pug">
section#root
  nuxt/
  FooterPart/
</template>

<script>
import FooterPart from '../components/footer/Footer.vue'
export default {
  components: {
    FooterPart
  }
}
</script>

<style lang="stylus">
html, body
  height 100%
#root
  display flex
  height 100vh
  flex-direction column
  align-items center
  justify-content center
</style>
