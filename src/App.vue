<script>
import Button from './components/Button.vue'

export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    }
  },

  components: {
    Button
  },

  methods: {
    //funzioni
  }
}

</script>

<template>

  <h1 class="title">
    {{ message }}
  </h1>

  <Button></Button>

</template>

<style scoped>
  .title {
    color: brown;
  }

</style>
