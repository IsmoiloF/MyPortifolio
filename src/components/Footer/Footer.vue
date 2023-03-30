<template>
  <div>
    <footer class="bg-[#1D1D1D] dark:bg-gray-800">
      <div
        class="w-full mx-auto container md:p-6 p-4 md:flex md:items-center md:justify-between"
      >
        <span class="text-indigo-100 sm:text-center dark:text-gray-400"
          >© 2023 All Rights Reserved.
        </span>
        <ul
          class="flex flex-wrap items-center mt-3 text-sm text-gray-500 dark:text-gray-400 sm:mt-0"
        >
          <li>
            <a href="#" class="mr-4 hover:text-[#13FF00] md:mr-6 text-indigo-100"
              >About</a
            >
          </li>
          <li>
            <a href="#" class="mr-4 hover:text-[#13FF00] md:mr-6 text-indigo-100"
              >Privacy Policy</a
            >
          </li>
          <li>
            <a href="#" class="mr-4 hover:text-[#13FF00] md:mr-6 text-indigo-100"
              >Licensing</a
            >
          </li>
          <li>
            <a href="#" class="hover:text-[#13FF00] text-indigo-100">Contact</a>
          </li>
        </ul>
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
