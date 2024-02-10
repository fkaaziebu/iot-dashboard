<script setup>
definePageMeta({
  layout: "auth",
});

import Register from "~/components/auth/register/Register.vue";
</script>

<template>
  <div class="flex items-center justify-center bg-blue-600 w-full h-screen">
    <Register />
  </div>
</template>
