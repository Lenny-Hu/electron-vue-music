<template lang='jade'>
  .m-home 首页
</template>

<script>
  export default {
    name: 'home',
    methods: {
      open (link) {
        this.$electron.shell.openExternal(link)
      }
    }
  }
</script>

<style scoped>
.m-home{
  
}
</style>
