<template>
  <div class="tpl">
    {{msg}}
  </div>
</template>
<script>
  //曝露出对象
  export default {
    data() {
      return {
        msg: "hehe~~~"
      }
    }
  }
</script>
<style>
.tpl{
  color:pink
}
</style>