<template>
  <div class="container mx-auto my-10">
    <div class="flex space-x-3">
      <bin />

      <pokemon />
    </div>
  </div>
</template>

<script setup>
  import bin from './components/bin.vue'
  import pokemon from './components/pokemon.vue'
</script>
