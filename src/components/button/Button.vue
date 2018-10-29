<template>
  <div>
    <h3>{{ label }}</h3>
    <button>{{ text }}</button>
  </div>
</template>

<script>
export default {
  name: 'Button',
  props: {
    text: String,
    label: String
  }
}
</script>

<style scoped>
h3 {
  color: #42b983;
  margin: 40px 0 0;
}
</style>
