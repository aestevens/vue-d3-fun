<template>
  <div id="app">
	<h1>Nimbus</h1>
	<h5>Network Activity Monitor</h5>
	
	<svg id="network-data"></svg>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  data: () => {
    return {
      seen: true
	}
  },
  components: {
    HelloWorld
  },
  methods: {
  }
}
</script>

<style>
body {
  background-color: #415059;
  font-family: Helvetica, Arial, sans-serif;
  text-align: center;
  color: #fff;
}

#app {
  
}
</style>
