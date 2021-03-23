<template>
  <div>
    <h1>Hello world</h1>
    <p> Hola mundo desde component Hello {{ dataH }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
    return{
      dataH:"Data desde H"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only cambio en comentarios-->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
