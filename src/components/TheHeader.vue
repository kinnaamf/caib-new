<script setup lang="ts">

import TheLogo from "@/components/TheLogo.vue";
import AppointmentButton from "@/components/AppointmentButton.vue";
</script>

<template>
  <div class="header">
    <the-logo></the-logo>
    <ul class="flex gap-15">
      <li>
        <router-link to="">Despre</router-link>
      </li>
      <li>
        <router-link to="">De ce noi</router-link>
      </li>
      <li>
        <router-link to="">Contacte</router-link>
      </li>
    </ul>
    <appointment-button></appointment-button>
  </div>
</template>

<style scoped>
  .header {
    @apply flex items-center justify-between text-[28px] font-medium;
  }
</style>
