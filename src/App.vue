<template>
  <!-- <img src="./assets/ico.jpg" /> -->
  <HelloWorld :msg="msg.text" />
</template>

<script setup>
import msg from "./msg"
//https://github.com/vuejs/rfcs/blob/master/active-rfcs/0040-script-setup.md
import HelloWorld from "./components/HelloWorld.vue"
</script>
