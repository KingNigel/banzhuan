<template>
  <div class="template">
    {{msg}}
  </div>
</template>
<script>
  export default {
    //和前面学的定义组件使用方式一样，必须返回一个对象
    data() {
      return { msg: "son" }
    }
  } 
</script>
<style>
.template{
  color:pink;
}
</style>