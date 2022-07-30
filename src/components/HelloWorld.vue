<script setup lang="ts">
import { ref } from "vue"
import logoUrl from "../assets/ico.jpg"
defineProps<{ msg: string }>()
const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <img :src="logoUrl" />
  <div>
    <button type="button" @click="count++">count is: {{ count }}</button>
  </div>
</template>
