<script setup lang="ts">

import TheLogo from "@/components/TheLogo.vue";
import AppointmentButton from "@/components/AppointmentButton.vue";
import HeaderNav from "@/components/HeaderNav.vue";
</script>

<template>
  <div class="header">
    <the-logo></the-logo>
    <header-nav></header-nav>
    <appointment-button></appointment-button>
  </div>
</template>

<style scoped>
  .header {
    @apply flex items-center justify-between text-[28px] font-medium;
  }
</style>
