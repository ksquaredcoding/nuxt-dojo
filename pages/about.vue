<template>
  <div>
    <h2>About</h2>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odio esse vel odit quo vero eius quam ab officiis
      earum. Possimus!</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odio esse vel odit quo vero eius quam ab officiis
      earum. Possimus!</p>
    <div>{{ data }}</div>
  </div>
</template>


<script setup>

const { data } = await useFetch('/api/ninja')

</script>


<style scoped>

</style>