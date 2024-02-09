<script setup>
definePageMeta({
  layout: "auth",
});

import Login from "~/components/auth/login/Login.vue";
</script>

<template>
  <div class="flex items-center justify-center bg-blue-600 w-full h-screen">
    <Login />
  </div>
</template>
