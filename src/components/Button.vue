<script>

export default {
  data() {
    return {
      count: 0
    }
  }
}

</script>

<template>
  <button @click="count++">
    Clicked here {{ count }} times
   </button>
</template>