<template>
  <div class="hello">
    <h1>La mia prima app con Vue CLI!</h1>
  </div>
</template>

<script>
export default {
  name: 'Title',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
    color: red;
}
</style>