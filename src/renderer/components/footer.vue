<template lang='jade'>
  .m-footer.u-top-line 尾巴
</template>

<script>
  export default {
    name: 'footer',
    methods: {
      open (link) {
        this.$electron.shell.openExternal(link)
      }
    }
  }
</script>

<style scoped>
.m-footer{
  height: 50px;
  background-color: #F6F6F8;
}
</style>
