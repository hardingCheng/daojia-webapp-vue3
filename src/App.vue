<template>
  <router-view />
  <Docker />
</template>
<script>
import Docker from './views/home/Docker.vue'
export default {
  name: 'App',
  components: {
    Docker
  }
}
</script>

<style lang="scss"></style>
