<template lang='jade'>
  .m-header 头部
</template>

<script>
  export default {
    name: 'header',
    methods: {
      open (link) {
        this.$electron.shell.openExternal(link)
      }
    }
  }
</script>

<style scoped>
.m-header{
  height: 50px;
  background-color: #C62F2F;
}
</style>
