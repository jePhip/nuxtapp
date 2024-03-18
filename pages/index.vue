<template>
  <h1>{{ store.count }}</h1>
    <v-btn @click="store.increment">increment</v-btn>
</template>

<script setup>
import { useCounterStore } from '@/store/counter'

// access the `store` variable anywhere in the component ✨
const store = useCounterStore()

</script>


<style>

</style>