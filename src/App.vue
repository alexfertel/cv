<template>
  <div class="antialiased">
    <div class="min-h-screen">
      <!-- Header -->
      <div class="ml-6 mt-6 flex items-center">
        <div class="flex items-center">
          <img
            class="h-10 w-h-10 rounded-full"
            src="/img/profile.jpg"
            alt="profile"
          />
          <span class="ml-8 text-lg text-gray-100 font-extrabold">
            Alexander González
          </span>
        </div>
        <svg
          class="h-6 w-6 text-white sm:hidden"
          viewBox="0 0 24 24"
        >
          <path
            stroke="currentColor"
            stroke-width="2"
            d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
          />
        </svg>
      </div>

      <!-- Tabs -->
      <Tabs/>

      <!-- About-->
      <p class="">
        Hello there! I am a 22 years old computer scientist graduated from 
        the University of Havana.
      </p>

    </div>
  </div>
</template>

<script>
import Tabs from "./components/Tabs";

export default {
  name: "app",
  components: {
    Tabs
  }
};
</script>

<style src="./assets/tailwind.css"></style>
