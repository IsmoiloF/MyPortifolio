<template>
  <div class="bg-[#1D1D1D]">
    <div id="Service" class="service pt-[150px] min-h-screen container mx-auto">
      <div class="justify-center items-center flex">
        <h1 class="text-[35px] text-white font-bold">My Services</h1>
      </div>

      <div
        class="cards grid-rows-3 flex gap-4 mx-auto justify-between mt-[50px]"
      >
        <div
          class="w-[450px] bg-[#161616] h-[300px] border border-[#161616] rounded-md hover:shadow-xl shadow-2xl hover:bg-transparent"
        >
          <div class="w-full justify-center items-center flex mt-[30px] text-white">
            <img class="w-[100px] text-[#13FF00]" src="../images/bx-code-blockweb.png" alt="" />
          </div>
          <div class="text-center">
            <h1 class="mt-[20px] text-[30px] text-white">Web Development</h1>
            <p class="mt-[10px] text-white">Blog, E-Commerce</p>
          </div>
        </div>
        <div
          class="w-[450px] bg-[#161616] h-[280px] border border-[#161616] shadow-2xl rounded-md hover:shadow-xl  hover:bg-transparent"
        >
          <div class="w-full justify-center items-center flex">
            <img
              class="w-[80px] mt-[35px]"
              src="../images/Vectoruii.png"
              alt=""
            />
          </div>
          <div class="text-center">
            <h1 class="mt-[20px] text-[30px] text-white">UI/UX Design</h1>
            <p class="text-white mt-[10px]">Mobile app, website design</p>
          </div>
        </div>
        <div
          class="w-[450px] bg-[#161616] h-[280px] border border-[#161616] shadow-2xl rounded-md hover:shadow-xl hover:bg-transparent"
        >
          <div class="w-full justify-center mt-[35px] items-center flex">
            <img class="w-[60px]" src="../images/Vectormobila.png" alt="" />
          </div>
          <div class="text-center">
            <h1 class="mt-[20px] text-[30px] text-white">Mobilagraph</h1>
            <p class="mt-[10px] text-white">portrait, product photography</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ServiceView",
};
</script>
<style></style>
