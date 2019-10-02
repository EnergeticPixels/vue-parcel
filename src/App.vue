<template>
  <div class='container'>
    <h1>{{ message }}</h1>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Using parcel in a vue.js (version 2) app'
    };
  }
}
</script>

<style scoped>
  .container {
    width: 600px;
    margin: 50px auto;
    text-align: center;
  }
</style>