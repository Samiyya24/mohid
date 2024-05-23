<script>
export default {
  data() {
    return {
      images: [
        "../src/assets/img/apple1.png",
        "../src/assets/img/apple2.png",
        "../src/assets/img/apple3.png",
        "../src/assets/img/apple4.png",
        "../src/assets/img/samsung.png",
        "../src/assets/img/fitBitMax.png",
      ],
      stars: [
        "../src/assets/img/Vector.svg",
        "../src/assets/img/Vector.svg",
        "../src/assets/img/Vector.svg",
        "../src/assets/img/Vector.svg",
        "../src/assets/img/Vector.svg",
      ],
      watchName: [
        "Apple Smart I",
        "Apple Smart II",
        "Apple Smart III",
        "Apple Smart IV",
        "Samsung Watch Pro",
        "Fitbit Max 1",
      ],
      sale: ["$300.00", "$300.00", "$300.00", "$450.00", "$300.00"],
      price: ["$255.00", "$255.00", "$255.00", "$399.00", "$255.00", "$155.00"],
      watchInfo: [
        "Apple is one of the most famous smart watches providing company.",
        "Xiaomi smart watches are produced by MI company.",
        "FitBit smart watches are best for their health and fitness features.",
      ],
    };
  },
};
</script>
<template>
  <div class="container mb-10">
    <div class="text-center">
      <h2 class="text-base text-[#3858D6] font-medium mb-5">
        Find your favourite smart watch.
      </h2>
      <h2 class="text-4xl font-bold">Our Latest Products</h2>
    </div>
    <div class="grid grid-cols-3">
      <div
        v-for="(img, index) in images"
        :key="index"
        class="p-10 text-center relative group"
      >
        <img
          :src="img"
          :alt="watchName[index]"
          class="bg-[#F6F6F6] px-12 py-7 mb-3"
        />

        <div
          class="text-white absolute top-12 right-20 group-hover:block hidden"
        >
          <svg
            class="bg-[#3858D6] mb-2 p-1 rounded-full"
            xmlns="http://www.w3.org/2000/svg"
            width="38px"
            height="38px"
            viewBox="0 0 24 24"
          >
            <path
              fill="currentColor"
              d="M21.822 7.431A1 1 0 0 0 21 7H7.333L6.179 4.23A1.994 1.994 0 0 0 4.333 3H2v2h2.333l4.744 11.385A1 1 0 0 0 10 17h8c.417 0 .79-.259.937-.648l3-8a1 1 0 0 0-.115-.921"
            />
            <circle cx="10.5" cy="19.5" r="1.5" fill="currentColor" />
            <circle cx="17.5" cy="19.5" r="1.5" fill="currentColor" />
          </svg>
          <svg
            class="bg-[#FF6B6B] p-1 rounded-full"
            xmlns="http://www.w3.org/2000/svg"
            width="38px"
            height="38px"
            viewBox="0 0 256 256"
          >
            <path
              fill="currentColor"
              d="M240 102c0 70-103.79 126.66-108.21 129a8 8 0 0 1-7.58 0C119.79 228.66 16 172 16 102a62.07 62.07 0 0 1 62-62c20.65 0 38.73 8.88 50 23.89C139.27 48.88 157.35 40 178 40a62.07 62.07 0 0 1 62 62"
            />
          </svg>
        </div>

        <div class="">
          <h3 class="text-2xl font-medium mb-2">{{ watchName[index] }}</h3>
          <div class="flex gap-1 ml-32 mb-2.5">
            <div v-for="(star, index) in stars" :key="index">
              <img :src="star" alt="" />
            </div>
          </div>
          <p class="text-2xl font-semibold">
            <span class="text-[#8B8E99] font-medium text-base line-through">{{
              sale[index]
            }}</span>
            {{ price[index] }}
          </p>
        </div>
      </div>
    </div>
    <button
      class="bg-[#3858D6] ml-[600px] text-lg font-medium py-2 px-5 rounded-xl text-white text-center"
    >
      View More
    </button>
  </div>
</template>
