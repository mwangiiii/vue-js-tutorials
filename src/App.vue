<template>
  <div>{{greeting}} {{ name }}</div>
  <br>
  <div v-text="channel_studying_using"> </div>
</template>

<script>


export default {
  name: 'App',
  data(){
    return {
      greeting:"hey",
      name: "wanjiku",
      channel_studying_using: "codevolution",
    };
  },
 
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; 
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
