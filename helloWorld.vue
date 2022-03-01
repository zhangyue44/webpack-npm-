<template>
  <div>
    <div>哈哈哈哈哈哈哈哈哈</div>
    <div>test</div>
    <div class="magclass">{{msg}}</div>
  </div>
</template>

<script>
export default {
  props: {
    msg: {
      type: String,
      default: ''
    }
  }
}
</script>

<style>
.magclass {
  color: red;
}
</style>
