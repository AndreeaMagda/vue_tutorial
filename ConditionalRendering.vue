<script>
export default {
  data() {
    return {
      awesome: true
    }
  },
  methods: {
    toggle() {
      this.awesome = !this.awesome
    }
  }
}
</script>

<template>
  <button @click="toggle">toggle</button>
  <h1 v-if="awesome">Avada Kedavra🪄</h1>
  <h1 v-else>Oh no, i am dead ☠️</h1>
</template>