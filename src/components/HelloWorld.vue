<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
<div class="animated-text">
  i LUV LATINAS!!!!
</div>
</template>



<style scoped>
.animated-text {
  animation: slide-in 1s ease-in-out infinite;
}

@keyframes slide-in {
  0% {
    transform: translateX(-100%) rotate(-90deg) scale(0%);

  }
  100% {
    transform: translateX(0%) rotate(90deg) scale(100%);


  }
}
</style>
