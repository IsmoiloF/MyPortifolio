<template>
  <div id="Service" class="service pt-[150px] min-h-screen container mx-auto">
    <div class="justify-center items-center flex ">
      <h1 class="text-[35px] text-white font-bold">My Services</h1>

    </div>

    <div class="cards grid-rows-3 flex gap-4 mx-auto justify-between mt-[50px]">
      <div class="w-[450px] bg-white h-[300px]  border  rounded-md hover:shadow-md hover:bg-indigo-200">
        <div class="w-full justify-center items-center flex my-[30px]"><img class="w-[100px]" src="../images/Groupweb.png" alt=""></div>
        <div class="text-center">
          <h1 class="my-[10px] text-[30px]">Web Development</h1>
          <p>Blog, E-Commerce</p>
        </div>
      </div>
      <div class="w-[450px] bg-white h-[300px]  border  rounded-md hover:shadow-md hover:bg-indigo-200">
        <div class="w-full justify-center items-center flex "><img class="w-[100px] my-[18px] " src="../images/Vectorui.png" alt=""></div>
        <div class="text-center">
          <h1 class="my-[10px] text-[30px]">UI/UX Design</h1>
          <p>Mobile app, website design</p>
        </div>
      </div>
      <div class="w-[450px] bg-white h-[300px]  border  rounded-md hover:shadow-md hover:bg-indigo-200">
        <div class="w-full justify-center items-center flex "><img class="w-[100px]" src="../images/Groupphotagraph.png" alt=""></div>
        <div class="text-center">
          <h1 class="my-[10px] text-[30px]">photography</h1>
          <p>portrait, product photography</p>
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
