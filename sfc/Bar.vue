<template>
  <div class="bar">
    <h1 class="header">Barコンポーネント</h1>
    <p>これはbarコンポーネント</p>
    <Foo />
  </div>
</template>
<script>
import Foo from './Foo'
export default {
  components: {
    Foo
  }
}
</script>
<style scoped>
.bar {
  border: 1px solid red;
  margin: 4px;
  padding: 4px;
}
.header {
  font-size: 125%;
}
</style>