<template>
  <section id="Portifolio"  class=" bg-[#202020] pb-20">
    <div class="container mx-auto">
      <div class="flex flex-col justify-between items-center">
        <h1 class="text-[40px] text-center pt-[146px] text-white  font-bold">Projects</h1>
        <div class="w-[35px] mt-3 border-t border-[#13FF00] border-[2px]"></div>
      </div>
      <swiper
        :slidesPerView="3"
        :spaceBetween="20"
        :pagination="{
          clickable: true,
        }"
        :modules="modules "
        :breakpoints="swiperOptions.breakpoints"
        class="mySwiper"
      >
        <swiper-slide>
          <div class="flex flex-col shadow-xl bg-[#272727] rounded-xl">
            <img
              src="../images/unsplash_cZr2sgaxy3Qporti.png"
              alt="img"
              class="rounded-t-xl"
            />
            <div class="p-4">
              <h3 class="text-[18px] mt-[20px]">Portfolio Website UI</h3>
              <div class="flex items-center mt-[6px]">
                <i class="bx bx-code-alt text-[#13FF00] text-[25px]"></i>
                <span class="text-[14px] text-slate-500">Web Development</span>
              </div>
              <div class="flex items-center justify-between mt-5">
                <a href="#" class="flex items-center gap-5">
                  <p>View code</p>
                  <i class="bx bx-arrow-back rotate-180"></i>
                </a>
                <button class="bg-[#13FF00] px-4 py-1 rounded-md">
                  Live Preview
                </button>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="flex flex-col shadow-xl bg-[#272727] rounded-xl">
            <img
              src="../images/unsplash_cZr2sgaxy3Qporti.png"
              alt="img"
              class="rounded-t-xl"
            />
            <div class="p-4">
              <h3 class="text-[18px] mt-[20px]">Portfolio Website UI</h3>
              <div class="flex items-center mt-[6px]">
                <i class="bx bx-code-alt text-[#13FF00] text-[25px]"></i>
                <span class="text-[14px] text-slate-500">Web Development</span>
              </div>
              <div class="flex items-center justify-between mt-5">
                <a href="#" class="flex items-center gap-5">
                  <p>View code</p>
                  <i class="bx bx-arrow-back rotate-180"></i>
                </a>
                <button class="bg-[#13FF00] px-4 py-1 rounded-md">
                  Live Preview
                </button>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="flex flex-col shadow-xl bg-[#272727] rounded-xl">
            <img
              src="../images/unsplash_cZr2sgaxy3Qporti.png"
              alt="img"
              class="rounded-t-xl"
            />
            <div class="p-4">
              <h3 class="text-[18px] mt-[20px]">Portfolio Website UI</h3>
              <div class="flex items-center mt-[6px]">
                <i class="bx bx-code-alt text-[#13FF00] text-[25px]"></i>
                <span class="text-[14px] text-slate-500">Web Development</span>
              </div>
              <div class="flex items-center justify-between mt-5">
                <a href="#" class="flex items-center gap-5">
                  <p>View code</p>
                  <i class="bx bx-arrow-back rotate-180"></i>
                </a>
                <button class="bg-[#13FF00] px-4 py-1 rounded-md">
                  Live Preview
                </button>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="flex flex-col shadow-xl bg-[#272727] rounded-xl">
            <img
              src="../images/unsplash_cZr2sgaxy3Qporti.png"
              alt="img"
              class="rounded-t-xl"
            />
            <div class="p-4">
              <h3 class="text-[18px] mt-[20px]">Portfolio Website UI</h3>
              <div class="flex items-center mt-[6px]">
                <i class="bx bx-code-alt text-[#13FF00] text-[25px]"></i>
                <span class="text-[14px] text-slate-500">Web Development</span>
              </div>
              <div class="flex items-center justify-between mt-5">
                <a href="#" class="flex items-center gap-5">
                  <p>View code</p>

                  <i class="bx bx-arrow-back rotate-180"></i>
                </a>
                <button class="bg-[#13FF00] px-4 py-1 rounded-md">
                  Live Preview
                </button>
              </div>
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="flex flex-col shadow-xl bg-[#272727] rounded-xl">
            <img
              src="../images/unsplash_cZr2sgaxy3Qporti.png"
              alt="img"
              class="rounded-t-xl"
            />
            <div class="p-4">
              <h3 class="text-[18px] mt-[20px]">Portfolio Website UI</h3>
              <div class="flex items-center mt-[6px]">
                <i class="bx bx-code-alt text-[#13FF00] text-[25px]"></i>
                <span class="text-[14px] text-slate-500">Web Development</span>
              </div>
              <div class="flex items-center justify-between mt-5">
                <a href="#" class="flex items-center gap-5">
                  <p>View code</p>
                  <i class="bx bx-arrow-back rotate-180"></i>
                </a>
                <button class="bg-[#13FF00] px-4 py-1 rounded-md">
                  Live Preview
                </button>
              </div>
            </div>
          </div>
        </swiper-slide>
      </swiper>
    </div>
  </section>
</template>

<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

import "swiper/css/pagination";

// import './style.css';

// import required modules
import { Pagination } from "swiper";

export default {
  name: "PortifolioView",
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Pagination],
      swiperOptions:{
        breakpoints:{
          320:{
            slidesPerView:1,
            spaceBetween:0,
          },
          770:{
            slidesPerView:2,
            spaceBetween:15
          },
          1024:{
            slidesPerView:3,
            spaceBetween:20
          },
          1350:{
            slidesPerView:4,
            spaceBetween:20
          }
        }
      }
    };
  },
};
</script>
<style lang="css">
.clippy {
  clip-path: polygon(
    50% 0%,
    83% 12%,
    100% 43%,
    94% 78%,
    68% 100%,
    32% 100%,
    6% 78%,
    0% 43%,
    17% 12%
  );
  border: 5px solid green;
}

.swiper {
  width: 100%;
  height: 700px;
}

.swiper-slide {
  background: #202020;

  /* Center slide text vertically */
  display: flex;
  justify-content: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.swiper-pagination-bullet-active {
  background: #13ff00 !important;
  transform: scale(1.5);
  box-shadow: inset 0 0 10px #13ff00, 0 0 10px #13ff00 !important;
}
</style>
