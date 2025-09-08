<template>
  <div>
    <h1>OK</h1>
    <input type="checkbox" v-model="checked" />
    <h1 v-if="checked">Checkbox is checked.</h1>
  </div>
</template>

<style>
  h1 {
    color: red;
  }
</style>

<script>
  export default {
    data() {
      return {
        checked: false
      }
    }
  }
</script>