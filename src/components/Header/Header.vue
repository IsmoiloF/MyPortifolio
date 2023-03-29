<template>
  <div class=" fixed w-[100%] shadow-md bg-[#202020]">
    <nav
      class="  border-gray-200 px-2 sm:px-4 py-2.5 dark:bg-gray-900 bg-[#202020]"
    >
      <div
        class="container flex flex-wrap items-center md:justify-between mx-auto"
      >
        <div class="w-[100%] md:w-auto flex justify-between">
          <a
            href="https://github.com/IsmoiloF?tab=repositories"
            class="flex items-center"
          >
            <span
              class=" text-[#13FF00] self-center text-[30px] font-semibold whitespace-nowrap dark:text-white"
              >DarkDP</span
            >
          </a>

          <span class="text-3xl cursor-pointer md:hidden block ">
            <i @click="openMenu" v-if="!isMenuOpen" class="bx bx-menu text-white"></i>
            <i @click="openMenu" v-if="isMenuOpen" class="bx bx-x text-white"></i>
          </span>
        </div>

        <div class="w-full md:block md:w-auto" id="navbar-default">
          <ul
            :class="[isMenuOpen ? 'flex' : 'hidden']"
            id="Nav"
            class="navbar md:flex flex-col p-4 mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0"
          >
            <li class="">
              <a
                href="#"
                class="active block py-2 pl-3 pr-4 text-white hover:text-[#13FF00]"
                aria-current="page"
                >Home</a
              >
            </li>
            <li>
              <a
                href="#About"
                class="active block py-2 pl-3 pr-4 text-white hover:text-[#13FF00]"
                >About</a
              >
            </li>
            <li>
              <a
                href="#Service"
                class="block py-2 pl-3 pr-4 text-white hover:text-[#13FF00]"
                >Services</a
              >
            </li>
            <li>
              <a
                href="#Portifolio"
                class="block py-2 pl-3 pr-4 text-white hover:text-[#13FF00]"
                >Portifolio</a
              >
            </li>
            <li>
              <a
                href="#Contact"
                class="block py-2 pl-3 pr-4 text-white hover:text-[#13FF00]"
                >Contact</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: "Header",
  data() {
    return {
      isMenuOpen: false,
    };
  },
  methods: {
    openMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    },
  },
};
</script>
<style setup>
.router-link-active {
  color: rgb(4, 0, 255) !important;
  text-decoration: undefined;
}

@media screen and (min-width: 756px) {
  .navbar {
    display: flex !important;
  }
}
</style>
