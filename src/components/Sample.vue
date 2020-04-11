<template>
  <div>
  <h2>v-if vs v-show</h2>
  <h6>v-if directive</h6>
   <p v-if="true">Hello</p>
   <p v-if="false">World</p>

    <h6>v-show directive</h6>
    <p v-show="false">Hello</p>
   <p v-show="true">World</p>
  </div>
</template>

<script>
export default {
  name: "sample",
 
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>
