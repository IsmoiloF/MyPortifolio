<template>
<div class=" bg-[#161616]">
  <div id="About" class="min-h-screen about container mx-auto flex justify-center gap-[100px]  items-center ">
    <div class="w-[500px] border rounded-[50%] border-[#13FF00] ">
      <img src="../images/hh.jpg" alt="" class="border border-[#13FF00] rounded-[50%] border-[3px]">
    </div>
    <div class="w-[500px]">
      <h1 class="font-bold text-white text-[35px]">About <span class="text-[#13FF00]">Me</span></h1>
      <p class="text-gray-300 text-[20px]">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo neque
        perferendis laborum, itaque expedita facere! Iure quibusdam, sunt earum
        non beatae et, modi praesentium aliquam enim laudantium quaerat magnam
        obcaecati numquam, sequi veniam? Iste perspiciatis quae voluptates optio
        dolorum ad.
      </p>
      <div class="w-[160px] mt-[20px] h-[55px] bg-transparent hover:bg-[#13FF00] border border-[#13FF00] rounded-md flex justify-center items-center ">
        <a href="#" class="w-[80%] text-[#13FF00] hover:text-white h-[100%] text-[22px] justify-center items-center flex">Read More</a>
        <span class="justify-center items-center flex hover:text-white"><i class='bx bx-right-arrow-alt text-[20px] text-[#13FF00] hover:text-white'></i></span>
      </div>
    </div>

  </div>
</div>
</template>
<script>
export default {
  name: "AboutView",
};
</script>
<style>
p {
  animation-duration: 3s;
  animation-name: slidein;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}</style>
