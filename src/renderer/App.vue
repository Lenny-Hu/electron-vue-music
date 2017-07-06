<template lang='jade'>
  #app.g-doc
    .g-hd
      m-header
    .g-bd
      router-view
    .g-ft
      m-footer
</template>

<script>
  import Header from './components/header.vue'
  import Footer from './components/footer.vue'
  export default {
    name: 'electron-vue-music',
    components: {
      'm-header': Header,
      'm-footer': Footer
    }
  }
</script>

<style lang='less'>
@import './assets/styles/function.less';
@import './assets/styles/main.less';
</style>
