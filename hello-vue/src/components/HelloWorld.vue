<template>
  <div>
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        hello 1
      </li>
      <li>
        test2
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'HelloWorld'
    }
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1{
    color: red;
  }
</style>
