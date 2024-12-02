<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>{{ count }}</h3>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    count: Number
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin-top: 2%;
}
h3 {
  margin: 40px 0 0;
}
</style>
