<template>
  <header>
    <div class="container">
      <nav class="py-3 flex items-center justify-between">
        <a href="#"><img src="../assets/img/icons/logo.svg" alt="" /></a>
        <ul class="flex divide-x">
          <li>
            <a
              class="text-[#70737C] uppercase text-sm hover:text-green-300 py-5 px-6"
              href="#"
              >ALL PRODUCTS</a
            >
          </li>
          <li>
            <a
              class="text-[#70737C] uppercase text-sm hover:text-green-300 py-5 px-6"
              href="#"
              >ABOUT SEEDRA</a
            >
          </li>
          <li>
            <a
              class="text-[#70737C] uppercase text-sm hover:text-green-300 py-5 px-6"
              href="#"
              >OUR BLOG</a
            >
          </li>
          <li>
            <a
              class="text-[#70737C] uppercase text-sm hover:text-green-300 py-5 px-7"
              href="#"
              >CONTACTS</a
            >
          </li>
        </ul>
        <div class="flex gap-3">
          <div class="flex gap-2">
            <img src="../assets/img/icons/instagram.svg" alt="" />
            <img src="../assets/img/icons/facebook.svg" alt="" />
          </div>
          <form action="" class="relative">
            <img
              class="absolute top-3 left-3"
              src="../assets/img/icons/icon_search.svg"
              alt=""
            />
            <input
              class="focus:outline-none border border-[#EFEFEF] px-12 py-3 rounded-full"
              type="text"
              placeholder="Search"
            />
          </form>
        </div>
        <div class="flex gap-2">
          <button>
            <img src="../assets/img/icons/heart.svg" alt="" />
          </button>
          <button>
            <img src="../assets/img/icons/cart.svg" alt="" />
          </button>
          <button class="block md:hidden">
            <img src="../assets/img/icons/Menu.svg" alt="" />
          </button>
        </div>
      </nav>
    </div>
  </header>
</template>

<script setup></script>

<style scoped></style>
