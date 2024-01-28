<template lang="pug">
b-img(:src="require('../assets/ruda.png')" fluid-grow)
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
