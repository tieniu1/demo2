<template>
  <div class="hello">
    <img alt="Vue logo" style="width: 100px;height: 100px;" src="@/assets/logo.png">
    <h1>hello world</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 .hello{
  text-align: center;
 }

</style>
