<template>
  <div id="app" class="w-3/5 mx-auto p-6">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to WeFlyp"/>
    <div class="bg-purple-600 text-white sm:bg-green md:bg-blue md:text-yellow lg:bg-red xl:bg-orange">
      Test
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>

</style>
