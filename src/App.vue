<script>

import AppJumbo from './components/AppJumbo.vue'

export default {
  name: 'App',
  components: {
    AppJumbo
  }
}
</script>

<template>
  <div class="container">
    ciao
    <AppJumbo />
  </div>
</template>

<style lang="scss">
  @use './styles/general';
</style>