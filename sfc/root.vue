<template>
  <div id="root">
    <h1 class="header">Rootコンポーネント</h1>
    <p>これはRootコンポーネント</p>
    <Foo />
    <Bar />
  </div>
</template>
<script>
import Foo from './Foo'
import Bar from './Bar'

export default {
  components: {
    Foo,
    Bar
  }
}
</script>
<style>
#root {
  border: 1px solid blue;
  margin: 4px;
  padding: 4px;
}
.header {
  font-size: 200%;
}
p {
  text-decoration: underline;
}
</style>