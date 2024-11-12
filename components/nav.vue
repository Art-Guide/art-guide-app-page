<template>
  <ul
    class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0 md:bg-white"
  >
    <li>
      <NuxtLink
        to="/"
        class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0"
        >Home</NuxtLink
      >
    </li>
    <li>
      <NuxtLink
        to="/privacy"
        class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0"
        >Privacy Policy</NuxtLink
      >
    </li>
    <li>
      <NuxtLink
        to="/terms"
        class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0"
        >Terms & Conditions</NuxtLink
      >
    </li>
    <li>
      <NuxtLink
        to="/delete"
        class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0"
        >Delete Account</NuxtLink
      >
    </li>
    <li>
      <NuxtLink
        to="mailto:alam.kanak@gmail.com"
        class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0"
        >Contact Us</NuxtLink
      >
    </li>
  </ul>
</template>

<style scoped>
.router-link-active {
  @apply text-white bg-blue-700 md:bg-transparent md:text-blue-700;
}
</style>
