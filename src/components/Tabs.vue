<template>
  <div>
    <ol class="mt-6 mx-2 flex">
      <li
        v-for="(item, index) in items"
        :key="index"
        class="ml-6 cursor-pointer hover:border-blue-800"
        @click="active = index"
      >
        <h3
          class="text-gray-400 font-semibold tracking-wide"
          :class="active == index ? 'border-b-2 border-solid border-red-500' : ''"
        >
          {{ item.title }}
        </h3>
      </li>
    </ol>
  </div>
</template>

<script>
export default {
  data() {
    return {
      active: 0,
      items: [
        { title: "About", active: true },
        { title: "Work", active: false },
        { title: "Contact", active: false }
      ]
    };
  }
};
</script>
