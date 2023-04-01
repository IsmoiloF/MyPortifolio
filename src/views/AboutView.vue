<template>
  <div class="bg-[#161616]">
    <div
      class="container mx-auto w-[80%] md:w-full pt-[60px] md:flex block md:justify-center md:gap-[300px] pb-[80px]"
    >
      <div class="">
        <div>
          <h1 class="text-[35px] font-bold text-white">Education</h1>
        </div>

        <div class="mt-[50px] flex flex-col gap">
          <p class="text-white text-[20px]">Fevral 2022 - Iyun 2022</p>
          <p class="text-[30px] text-[#13FF00]">Foundation course</p>
          <p class="text-white text-[20px]">Najot Ta'lim</p>
        </div>

        <div class="mt-[35px] flex flex-col gap">
          <p class="text-white text-[20px]">Avgust 2022 - Apriel 2023</p>
          <p class="text-[30px] text-[#13FF00]">Full Stack course (Node js)</p>
          <p class="text-white text-[20px]">Najot Ta'lim</p>
        </div>

        <div class="mt-[35px] flex flex-col gap">
          <p class="text-white text-[20px]">Sentabr 2021 - Iyul 2022</p>
          <p class="text-[30px] text-[#13FF00]">Robatatexnika</p>
          <p class="text-white text-[20px]">TDTU</p>
        </div>

        <div class="mt-[35px] flex flex-col gap">
          <p class="text-white text-[20px]">Sentabr 2022 - Iyul 2027</p>
          <p class="text-[30px] text-[#13FF00]">Axborat Xavfsizligi</p>
          <p class="text-white text-[20px]">TATU</p>
        </div>
      </div>

      <div>
        <div class="pt-[80px] md:pt-0">
          <h1 class="text-[35px] font-bold text-white">Job</h1>
        </div>

        <div class="mt-[30px] flex flex-col">
          <p class="text-white text-[20px]">Fevral 2023 - Iyun 2023</p>
          <p class="text-[30px] text-[#13FF00]">Lorem ipsum dolor sit.</p>
          <p class="text-white text-[20px]">Lorem, ipsum.</p>
        </div>
      </div>
    </div>

    <div
      id="About"
      class="min-h-screen about container mx-auto block md:flex justify-center gap-[150px] items-center"
    >
      <div
        class="md:w-[500px] mx-auto md:mx-0 mt-[60px] w-[380px]"
        data-aos="fade-right"
        data-aos-offset="300"
        data-aos-easing="ease-in-sine"
      >
        <img
          src="../images/hh.jpg"
          alt=""
          class="border border-[#13FF00] rounded-[50%] border-[3px]"
        />
      </div>

      <div
        class="w-[380px] md:w-[500px] mx-auto md:mx-0 xl:w-[400px] mt-[50px] md:mt-0"
        data-aos="fade-left"
        data-aos-offset="300"
        data-aos-easing="ease-in-sine"
      >
        <h1 class="font-bold text-white text-[35px]">
          About <span class="text-[#13FF00]">Me</span>
        </h1>
        <p class="text-gray-300 text-[20px]">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo neque
          perferendis laborum, itaque expedita facere! Iure quibusdam, sunt
          earum non beatae et, modi praesentium aliquam enim laudantium quaerat
          magnam obcaecati numquam, sequi veniam? Iste perspiciatis quae
          voluptates optio dolorum ad.
        </p>
        <div
          class="w-[160px] mt-[20px] h-[55px] bg-transparent hover:bg-[#13FF00] border border-[#13FF00] rounded-md flex justify-center items-center"
        >
          <a
            href="#"
            class="w-[80%] text-[#13FF00] hover:text-white h-[100%] text-[22px] justify-center items-center flex"
            >Read More</a
          >
          <span class="justify-center items-center flex hover:text-white"
            ><i
              class="bx bx-right-arrow-alt text-[20px] text-[#13FF00] hover:text-white"
            ></i
          ></span>
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
}
</style>
