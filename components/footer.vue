<template>
  <div class="py-10 flex flex-col items-center">
    <div class="flex justify-center gap-3 font-medium mb-4">
      <NuxtLink to="/" class="text-blue-700 hover:underline">Home</NuxtLink>
      <div class="text-gray-300">|</div>
      <NuxtLink to="/privacy" class="text-blue-700 hover:underline"
        >Privacy Policy</NuxtLink
      >
      <div class="text-gray-300">|</div>
      <NuxtLink to="/terms" class="text-blue-700 hover:underline"
        >Terms & Conditions</NuxtLink
      >
      <div class="text-gray-300">|</div>
      <NuxtLink
        to="mailto:alam.kanak@gmail.com"
        class="text-blue-700 hover:underline"
        >Contact Us</NuxtLink
      >
    </div>
    <div class="text-gray-400">
        Copyright © {{ new Date().getFullYear() }} Raquib Ul Alam.
    </div>
  </div>
</template>
