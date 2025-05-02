
<template>
  <Inputs label="username" placeholder="Your username" id="input1" class="helloworld" type="text" />
</template>
<script >
  import Inputs from './components/Templates/Inputs.vue'
  export default {
    name: 'App',
    components: {
      Inputs
    },
    data() {
        return {
            msg: 'Welcome to Your Vue.js App'
        }
    },
    }
</script>

<style>
</style>