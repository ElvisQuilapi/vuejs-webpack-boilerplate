<template>
  <div>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Vue Webpack & Bootstrap v3.3.7 Boilerplate.'
    }
  }
}
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
