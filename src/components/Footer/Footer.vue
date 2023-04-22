<template>
  <div>
    <footer class="bg-[#1D1D1D] dark:bg-gray-800">
      <div
        class="w-full mx-auto  flex container md:p-6 p-4 md:flex md:items-center md:justify-between"
      >
        <span class=" text-indigo-100 sm:text-center dark:text-gray-400"
          >©2023 Shoxruh Ismoilov.
        </span>
      </div>
    </footer>
  </div>
</template>
<script>
import { RouterLink } from "vue-router";

export default {
  name: "Footer",
  components: { RouterLink },
};
</script>
<style></style>
