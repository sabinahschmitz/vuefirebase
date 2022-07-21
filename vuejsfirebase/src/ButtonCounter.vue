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
  <button class="btn" @click="count++">You clicked me {{ count }} times.</button>
</template>

<style scoped>
.btn {
  color: #fff
}
</style>