<template>
    <div class="flex justify-center items-center h-screen">
       <div class="w-1/2">
         <h1 class="text-5xl  text-white bg-gray-400"> {{msg}} </h1>
  
       </div>
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
