<script>
export default {
  data() {
    return {
      images: [
        "../src/assets/img/apple.png",
        "../src/assets/img/xiaomi.png",
        "../src/assets/img/fitBit.png",
      ],
      watchName: ["Apple", "Xiaomi", "FitBit"],
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
  <div class="container mx-auto">
    <div class="flex py-16 gap-5">
      <div
        v-for="(img, index) in images"
        :key="index"
        class="flex items-center bg-[#F6F6F6] rounded-3xl p-10 gap-7"
      >
        <img :src="img" :alt="watchName[index]" />
        <div>
          <h3 class="text-4xl font-bold mb-2">{{ watchName[index] }}</h3>
          <p class="text-[#8B8E99] font-medium text-base max-w-[200px]">
            {{ watchInfo[index] }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
