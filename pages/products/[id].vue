<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci dignissimos, suscipit officiis consequatur eos, vero, enim facilis nesciunt est quas placeat! Odio, rerum enim harum alias nostrum est cumque facilis?</p>
  </div>
</template>

<script  setup>
const { id } =useRoute().params
</script>

<style>

</style>