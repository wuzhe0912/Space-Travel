<script setup>
import { ref } from 'vue';

const count = ref(0);
</script>

<template>
  <section class="mx-auto max-w-screen-xl rounded-lg bg-white p-8 shadow-2xl">
    <h2 class="my-6 text-3xl">Comments</h2>
    <form action="" class="grid">
      <textarea
        name="comment"
        id=""
        placeholder="Please input your comment"
        class="rounded bg-gray-50 p-2"
      ></textarea>
      <fieldset class="py-4">
        <input
          type="submit"
          value="Comment"
          class="cursor-pointer rounded bg-blue-600 px-4 py-1 text-white hover:bg-blue-500"
        />
        <input
          type="reset"
          value="Cancel"
          class="ml-3 cursor-pointer rounded border bg-white px-4 py-1 hover:bg-gray-50"
        />
      </fieldset>
    </form>
  </section>
</template>

<style scoped></style>
