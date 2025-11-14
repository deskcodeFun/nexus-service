<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header class="flex flex-row m-16 bg-amber-100">
    <RouterLink
      to="/"
      class="text-sm m-2 p-2 flex flex-col justify-center items-center hover:bg-amber-600"
    >
      <i class="material-symbols-outlined" style="font-size: 36px;font-weight: 300;"> home </i>

      Home
    </RouterLink>
    <RouterLink
      to="#"
      class="text-sm m-2 p-2 flex flex-col justify-center items-center hover:bg-amber-600"
    >
      <i class="material-symbols-outlined" style="font-size: 36px;font-weight: 300;">person </i>

      Staff
    </RouterLink>
    <RouterLink
      to="/about"
      class="text-sm m-2 p-2 flex flex-col justify-center items-center hover:bg-amber-600"
    >
      <i class="material-symbols-outlined" style="font-size: 36px;font-weight: 300;">info </i>
      <span>About</span>
    </RouterLink>
  </header>

  <RouterView />
</template>

<style scoped></style>
