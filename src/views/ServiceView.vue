<template>


  <div class="bg-[#1D1D1D]">
    <section
          id="services"
          class="container   main-content__services w-[75%] mx-auto py-[50px]"
        >
          <div class="title text-center mb-8">
            <h2 class="text-[32px] font-bold capitalize mb-4 text-white">my services</h2>
            <p class="max-w-[438px] text-[#fffc] mx-auto">
              I can offer several of my services for you. You can get acquainted
              with them below.
            </p>
          </div>
          <div class="flex justify-between flex-wrap">
            <!-- 1 -->
            <div
              class="card bg-[#242424] p-8 w-full sm:w-[48.5%] md:w-[32%] flex flex-col items-center mb-3 sm:mb-6"
            >
              <img
                src="../images/responsive.png"
                alt="card-image"
                class="mb-6 w-[100px] "
              />
              <h3 class="text-lg font-medium mb-2 capitalize text-white">
                Responsive Design
              </h3>
              <p class="text-[#fffc] text-[15px] text-center">
                Creating a responsive web template
              </p>
            </div>
            <!-- 2 -->
            <div
              class="card bg-[#242424] p-8 w-full sm:w-[48.5%] md:w-[32%] flex flex-col items-center mb-3 sm:mb-6"
            >
              <img
                src="../images/crm.png"
                alt="card-image"
                class="mb-6 w-[100px]"
              />
              <h3 class="text-lg font-medium mb-2 capitalize text-white">CRM systems</h3>
              <p class="text-[#fffc] text-[15px] text-center text-white">
                CRM systems to grow your business
              </p>
            </div>
            <!-- 3 -->
            <div
              class="card bg-[#242424] p-8 w-full sm:w-[48.5%] md:w-[32%] flex flex-col items-center mb-3 sm:mb-6"
            >
              <img
                src="../images/spa.png"
                alt="card-image"
                class="mb-6 w-[100px]"
              />
              <h3 class="text-lg font-medium mb-2 capitalize text-white">SPA</h3>
              <p class="text-[#fffc] text-[15px] text-center">
                Creating a Single Page Applications
              </p>
            </div>
            <!-- 4 -->
            <div
              class="card bg-[#242424] p-8 w-full sm:w-[48.5%] md:w-[32%] flex flex-col items-center mb-3 sm:mb-6"
            >
              <img
                src="../images/architect.png"
                alt="card-image"
                class="mb-6 w-[70px]"
              />
              <h3 class="text-lg font-medium mb-2 capitalize text-white ">
                backend architecture
              </h3>
              <p class="text-[#fffc] text-[15px] text-center">
                Building backend applications and their architecture
              </p>
            </div>
            <!-- 5 -->
            <div
              class="card bg-[#242424] p-8 w-full sm:w-[48.5%] md:w-[32%] flex flex-col items-center mb-3 sm:mb-6"
            >
              <img
                src="../images/bot.png"
                alt="card-image"
                class="mb-6 w-[100px]"
              />
              <h3 class="text-lg font-medium mb-2 capitalize text-white">telegram bot</h3>
              <p class="text-[#fffc] text-[15px] text-center">
                Creating all kinds of telegram bots
              </p>
            </div>
            <!-- 6 -->
            <div
              class="card bg-[#242424] p-8 w-full sm:w-[48.5%] md:w-[32%] flex flex-col items-center mb-3 sm:mb-6"
            >
              <img
                src="../images/hosting.png"
                alt="card-image"
                class="mb-6 w-[100px]"
              />
              <h3 class="text-lg font-medium mb-2 capitalize text-white">Hosting</h3>
              <p class="text-[#fffc] text-[15px] text-center">
                Domen, Hosting and SEO optimization
              </p>
            </div>
          </div>
        </section>
  </div>

</template>
<script>
export default {
  name: "ServiceView",
};
</script>
<style></style>
