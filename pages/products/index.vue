<template>
  <div>
    <div class="grid grid-cols-4 gap-5">
        <div v-for="p in products">
            <!-- <NuxtLink :to="`/products/${p.id}`">
              {{ p.category }}  
            </NuxtLink> -->
            <ProuductCard :product="p"/>
        </div>
    </div>
  </div>
</template>

<script setup>
definePageMeta({
    layout: 'products'
})
const {data: products}=await useFetch('https://fakestoreapi.com/products')
</script>

<style>

</style>