<template>
  <div class="home">
      <button class="button">This is a test button</button>
      <progress class="progress" value="15" max="100">15%</progress>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
// import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

export default defineComponent({
  name: 'HomeView',
  components: {
    // HelloWorld
  }
})
</script>

<style lang="sass" scoped>

.home
  padding: 1em

</style>
