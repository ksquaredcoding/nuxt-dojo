<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum illum ullam neque cum fuga obcaecati voluptate
      maxime est sapiente blanditiis.</p>
  </div>
</template>


<script>
export default {
  setup() {
    const { id } = useRoute().params
    return {
      id
    }
  }
}
</script>


<style scoped>

</style>