<template>
  <div class="antialiased">
    <div class="min-h-screen">
      <!-- Header -->
      <div class="ml-6 mt-6 flex items-center">
        <div class="flex items-center">
          <img
            class="h-12 w-h-12 rounded-full"
            src="/img/profile.jpg"
            alt="profile"
          />
          <span class="ml-8 text-2xl text-gray-200 font-extrabold">
            Alexander González Fertel
          </span>
        </div>
        <svg
          class="h-6 w-6 text-white hidden fill-current"
          viewBox="0 0 24 24"
        >
          <path
            d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
          />
        </svg>
      </div>

      <!-- Tabs -->
      <Tabs/>

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
