<template>
  <div class="bg-[#161616]">
    <section
      id="education"
      class="main-content__education container mx-auto w-[80%] mx-auto pb-16"
    >
      <div class="title text-center py-8">
        <h2 class="text-[32px] font-bold capitalize text-white mb-4">
          education
        </h2>
        <p class="max-w-[438px] text-[#fffc] mx-auto">
          Get to know the institutions where I studied
        </p>
      </div>
      <div class="bg-[#242424] p-6 sm:p-8">
        <!-- 1 -->
        <div
          class="flex flex-wrap md:flex-nowrap pb-6 border-b border-[#ffffff36] mb-8"
        >
          <div
            class="study-place w-full md:w-1/3 md:pr-3 2xl:pr-4 mb-7 md:mb-0"
          >
            <h3 class="text-lg mb-3 md:mb-7 font-medium text-white">
              Tashkent University of Information Technologies
            </h3>
            <div class="flex justify-between items-center">
              <span class="text-[#fffc] mr-2">Student</span>
              <span class="bg-[#13FF00] py-1 px-2 rounded-md text-sm"
                >Sep 2022 - June 2027</span
              >
            </div>
          </div>
          <div class="study-about w-full md:w-2/3 md:pl-6 2xl:pl-8">
            <h3 class="text-lg mb-3 md:mb-7 font-medium text-white">
              Information Security
            </h3>
            <p class="text-[#fffc]">
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum,
              hic!
            </p>
          </div>
        </div>
        <!-- 2 -->
        <div
          class="flex flex-wrap md:flex-nowrap pb-6 border-b border-[#ffffff36] mb-8"
        >
          <div
            class="study-place w-full md:w-1/3 md:pr-3 2xl:pr-4 mb-7 md:mb-0"
          >
            <h3 class="text-lg mb-3 md:mb-7 font-medium text-white">
              Najot Ta'lim
            </h3>
            <div class="flex justify-between items-center">
              <span class="text-[#fffc] mr-2">Student</span>
              <span class="bg-[#13FF00] py-1 px-2 rounded-md text-sm"
                >fev 2022 - June 2022</span
              >
            </div>
          </div>
          <div class="study-about w-full md:w-2/3 md:pl-6 2xl:pl-8">
            <h3 class="text-lg mb-3 md:mb-7 font-medium text-white">
              Foundation course
            </h3>
            <p class="text-[#fffc]">
              We covered the basics of programming in this course. We taught C,
              Python, programming languages.
            </p>
          </div>
        </div>

        <div
          class="flex flex-wrap md:flex-nowrap pb-6 border-b border-[#ffffff36] mb-8"
        >
          <div
            class="study-place w-full md:w-1/3 md:pr-3 2xl:pr-4 mb-7 md:mb-0"
          >
            <h3 class="text-lg mb-3 md:mb-7 font-medium">Najot Ta'lim</h3>
            <div class="flex justify-between items-center">
              <span class="text-[#fffc] mr-2">Student</span>
              <span class="bg-[#13FF00] py-1 px-2 rounded-md text-sm"
                >Aug 2022 - Apr 2023</span
              >
            </div>
          </div>
          <div class="study-about w-full md:w-2/3 md:pl-6 2xl:pl-8">
            <h3 class="text-lg mb-3 md:mb-7 font-medium">
              Node.js + Vue.js Full stack course
            </h3>
            <p class="text-[#fffc]">
              We have organized web programming (backand+frontend) during this
              course
            </p>
          </div>
        </div>
      </div>
    </section>

    <section
      id="work"
      class="container main-content__work w-[80%] mx-auto pb-16"
    >
      <div class="title text-center mb-8">
        <h2 class="text-[32px] font-bold capitalize mb-4 text-white">
          Work history
        </h2>
      </div>
      <div class="bg-[#242424] p-6 sm:p-8">
        <!-- 1 -->
        <div
          class="flex flex-wrap md:flex-nowrap pb-6 border-b border-[#ffffff36] mb-8"
        >
          <div class="work-place w-full md:w-1/3 md:pr-3 2xl:pr-4 mb-7 md:mb-0">
            <h3 class="text-lg mb-2 md:mb-7 font-medium text-white">
              Najot Ta'lim
            </h3>
            <div class="flex justify-between items-center">
              <span class="text-[#fffc] mr-2">Tashkent</span>
              <span class="bg-[#13FF00] py-1 px-2 rounded-md text-sm"
                >Mar 2023 - Apr 2023</span
              >
            </div>
          </div>
          <div class="work-about w-full md:w-2/3 md:pl-6 2xl:pl-8">
            <h3 class="text-lg mb-3 md:mb-7 font-medium text-white">
              Junior Fullstack developer (practise)
            </h3>
            <ul class="text-[#fffc] list-disc">
              <li>
                During the internship, the real project "Akmal express crm" was
                assigned to our team and I performed the role of team lead in
                this team
              </li>
              <li>I developed the main pages of the project using vue.js</li>
              <li>
                I integrated the frontend and backend parts of the project with
                the help of pinia state manager
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </div>
  <div class="bg-[#161616] pt-[20px]">
    <div
      id="About"
      class="min-h-screen about container mx-auto block md:flex justify-center gap-[150px] items-center"
    >
      <div class="about_image md:w-[500px]  mx-auto md:mx-0 mt-[60px] w-[380px]">
        <img
          src="../images/hh.jpg"
          alt=""
          class="border border-[#13FF00] rounded-[50%] border-[3px]"
        />
      </div>

      <div
        class="w-[80%] md:w-[500px] mx-auto md:mx-0 xl:w-[400px] mt-[50px] md:mt-0"
      >
        <h1 class="font-bold text-white text-[35px]">
          About <span class="text-[#13FF00]">Me</span>
        </h1>
        <p class="text-gray-300 text-[20px]">
          I am a full stack developer, I develop websites, Site
I can work in backend and frontend parts,I also have experience working with a team
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
@media only screen and (max-width: 600px) {
    .container {
      max-width: 580px;
    }
    .about_image{
      display: hidden;
      display: none;
    }
  }

</style>
