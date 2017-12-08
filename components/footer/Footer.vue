<template lang="pug">
  footer
    span
      | &copy; {{year}} HOMECINEMA &amp; AUDIO Co., Ltd.
</template>

<script>
export default {
  data () {
    return {
      year: new Date().getFullYear()
    }
  }
}
</script>
