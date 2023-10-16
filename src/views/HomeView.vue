<script setup>
import {useCounterStore} from '@/store/counter.js'

const useCounter = useCounterStore()
const {increment} = useCounter



</script>

<template>
 <h1>
  Home counter: {{ useCounter.count }}
 </h1>
 <h2>Doble: {{ useCounter.double}}</h2>
 <button @click="increment">increment</button>
</template>
