<template>
 <main>
<!-- Date -->

<div>
  {{ new Date().toLocaleDateString('en-us', {
    weekday: 'long',
    year:'numeric',
    month:'long',
    day: 'numeric'
  }) }}
</div>
 </main>
</template>

<script setup>
 
</script>

<style>

</style>