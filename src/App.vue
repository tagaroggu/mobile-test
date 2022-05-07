<script setup>
  import Extras from './components/Extra.vue';
  import { ref } from 'vue';

  const count = ref(0);
</script>

<template>
  This is a <strong>test</strong> of programming on a phone. Lots of mistakes will be made, but it's a <em>learning experience</em>.
  <br>
  Want to tally my mistakes with me? <button @click="count++">{{ count }}</button>
  <br>
  <Extras />
</template>

<style>

</style>
