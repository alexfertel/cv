<template>
  <div class="antialiased">
    <div class="min-h-screen">
      <!-- Header -->
      <div class="ml-6 mt-6 flex items-center">
        <div>
          <img
            class="h-10 w-h-10 rounded-full"
            src="/img/profile.jpg"
            alt="profile"
          />
          <span class="ml-4 text-lg text-gray-100 font-extrabold">
            Alexander A. González Fertel
          </span>
        </div>
        <svg class="fill">
          <path
            class="heroicon-ui"
            d="M4 5h16a1 1 0 010 2H4a1 1 0 110-2zm0 6h16a1 1 0 010 2H4a1 1 0 010-2zm0 6h16a1 1 0 010 2H4a1 1 0 010-2z"
          />
        </svg>
      </div>

      <!-- Tabs -->
      <!-- <Tabs/> -->
    </div>
  </div>
</template>

<script>
import Tabs from "./components/Tabs";

export default {
  name: "app",
  components: {
    // Tabs
  }
};
</script>

<style src="./assets/tailwind.css"></style>
