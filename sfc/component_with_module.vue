<template>
  <p :class="$style.message">メッセージ：{{ msg }}</p>
</template>
<script>
export default {
  data() {
    return {
      msg: 'hello'
    }
  },
  created() {
    // eslint-disable-next-line no-console
    console.log('css modules: $style', this.$style)
  }
}
</script>
<style module>
.message{
  color: #42b983;
}
</style>