<script setup>
  const links = {
    'My site': 'https://tagaroggu.github.io',
    'Repo': 'https://github.com/tagaroggu/mobile-test'
  };
</script>

<template>
  <a v-for="(v, k) in links" :href="v" :key="k">{{ k }} </a>
</template>
