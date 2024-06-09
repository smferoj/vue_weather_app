<script setup>
 import SearchInput from "./components/SearchInput.vue";

</script>



<template>
 <main>
<!-- Date -->

<div class="text-center mb-6">
  {{ new Date().toLocaleDateString('en-us', {
    weekday: 'long',
    year:'numeric',
    month:'long',
    day: 'numeric'
  }) }}
</div>
 
 <!-- Searchbar -->

<SearchInput />


 </main>
</template>

<script setup>
 
</script>

<style>

</style>