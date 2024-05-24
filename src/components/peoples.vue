<script>
export default {
  data() {
    return {
      images: ["../src/assets/img/Hamza.png", "../src/assets/img/Hafiz.png"],
      userName: ["Hamza Faizi", "Hafiz Huzaifa"],
      userComent: [
        "Don’t waste time, just order! This is the best website to puschase smart watches.",
        "I’ve been purchasing smart watches of Mohid for a long time. All the products are good quality.",
      ],
      stars: [
        "../src/assets/img/Vector.svg",
        "../src/assets/img/Vector.svg",
        "../src/assets/img/Vector.svg",
        "../src/assets/img/Vector.svg",
        "../src/assets/img/Vector.svg",
      ],
    };
  },
};
</script>

<template>
  <div class="container mx-auto">
    <div class="text-center">
      <h2 class="text-base text-[#3858D6] font-medium mb-5">
        Here are our some of the best clients.
      </h2>
      <h2 class="text-4xl font-bold">What People Say About Us</h2>
    </div>
    <div class="lg:flex py-16 justify-between gap-12">
      <div
        v-for="(img, index) in images"
        :key="index"
        class="flex items-center mb-3 bg-[#F6F6F6] rounded-3xl p-10 gap-7 w-full"
      >
        <img :src="img" :alt="userName[index]" />
        <div>
          <h3 class="text-2xl font-bold mb-2">{{ userName[index] }}</h3>
          <p class="text-[#8B8E99] font-medium mb-4 text-base max-w-[280px]">
            {{ userComent[index] }}
          </p>
          <div class="flex gap-1">
            <div v-for="(star, index) in stars" :key="index">
              <img :src="star" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="flex gap-2 ml-[600px]">
      <div class="w-5 h-5 bg-[#D9D9D9] hover:bg-[#3858D6] rounded-full"></div>
      <div class="w-5 h-5 bg-[#D9D9D9] hover:bg-[#3858D6] rounded-full"></div>
      <div class="w-5 h-5 bg-[#D9D9D9] hover:bg-[#3858D6] rounded-full"></div>
      <div class="w-5 h-5 bg-[#D9D9D9] hover:bg-[#3858D6] rounded-full"></div>
      <div class="w-5 h-5 bg-[#D9D9D9] hover:bg-[#3858D6] rounded-full"></div>
    </div>
  </div>
</template>

<style scoped></style>
