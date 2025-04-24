import { NuxtLink, NuxtImg } from '../.nuxt/components';
<script lang="ts" setup>

</script>


<template>
  <header class="py-4 border-b">
    <nav class="flex container items-center">
      <NuxtLink to="/" class="flex gap-1 items-center">
        <NuxtImg width="56px" src="icon-green.png" format="webp" alt="Logo" densities="x1" />
        <span class="text-3xl text-black">Nuxtcipes</span>
      </NuxtLink>
      <ul class="flex gap-6 ml-auto text-xl capitalize">
        <li>
          <NuxtLink class="nav-item" to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink class="nav-item" to="/about">About</NuxtLink>
        </li>
      </ul>
    </nav>
  </header>
</template>
