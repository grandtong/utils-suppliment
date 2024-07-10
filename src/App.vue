<template>
  <div id="app">
    <iframe-com></iframe-com>
  </div>
</template>

<script>
import { IframeCom } from 'compoment-demo'
import { timeFix } from 'compoment-demo/src/utils/util'
export default {
  name: 'App',
  components: {
    IframeCom
  }
}
alert(timeFix())
</script>

<style>
#app {
  display: flex;
  flex-direction: column;
}
</style>
