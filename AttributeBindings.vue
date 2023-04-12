<script>
export default {
  data() {
    return {
      titleClass: 'title'
    }
  }
}
</script>

<template>
  <h1 :class="titleClass">Make me violet</h1>
</template>

<style>
.title {
  color: violet;
}
</style>