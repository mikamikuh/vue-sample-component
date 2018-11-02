<template>
  <div>
    <h3>{{ label }}</h3>
    <input type="text" value="">{{ text }}</input>
  </div>
</template>

<script>
export default {
  name: 'Label',
  props: {
    label: String
  }
}
</script>

<style scoped>
h3 {
  color: #FF0000;
  margin: 40px 0 0;
}
</style>
