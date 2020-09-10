<template>
  <form @submit.prevent="onSubmit" class="flex bg-gray-200 border-4 border-blue-600 rounded-lg">
    <input
      type="email"
      placeholder="Enter your email..."
      class="flex-grow bg-gray-200 text-xl text-black px-2 rounded-lg m-1 mr-0"
      style="min-width:0"
    />
    <button
      type="submit"
      class="bg-blue-600 py-2 px-4 border-4 border-gray-200 rounded-lg"
    >Subscribe</button>
  </form>
</template>

<script>
export default {
  methods: {
    async onSubmit() {},
  },
};
</script>

<style>
</style>