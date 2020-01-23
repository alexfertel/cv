<template>
  <div>
    <ol class="mt-6 mx-2 flex border-b-2">
      <li class="ml-2 text-gray-700" :class="item.active ? 'bg-blue-500' : ''"
        v-for="(item, index) in items" :key="index">
        {{ item.title }}
      </li>
    </ol>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        { title: "Hi!", active: true },
        { title: "Hello!", active: false },
        { title: "Sup!", active: false }
      ]
    };
  }
};
</script>
