<template>
  <header class="bg-black text-[#8B8E99]">
    <div class="container">
      <nav class="flex items-center justify-between py-6">
        <a href="#"><img src="../assets/img/Logo.svg" alt="" /></a>

        <ul class="max-md:hidden flex gap-7">
          <li><a href="#">Home</a></li>
          <li class="flex items-center">
            <a href="#">Brands</a
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="1em"
              height="1em"
              viewBox="0 0 24 24"
            >
              <g fill="none" fill-rule="evenodd">
                <path
                  d="M24 0v24H0V0zM12.593 23.258l-.011.002l-.071.035l-.02.004l-.014-.004l-.071-.035c-.01-.004-.019-.001-.024.005l-.004.01l-.017.428l.005.02l.01.013l.104.074l.015.004l.012-.004l.104-.074l.012-.016l.004-.017l-.017-.427c-.002-.01-.009-.017-.017-.018m.265-.113l-.013.002l-.185.093l-.01.01l-.003.011l.018.43l.005.012l.008.007l.201.093c.012.004.023 0 .029-.008l.004-.014l-.034-.614c-.003-.012-.01-.02-.02-.022m-.715.002a.023.023 0 0 0-.027.006l-.006.014l-.034.614c0 .012.007.02.017.024l.015-.002l.201-.093l.01-.008l.004-.011l.017-.43l-.003-.012l-.01-.01z"
                />
                <path
                  fill="currentColor"
                  d="M13.06 16.06a1.5 1.5 0 0 1-2.12 0l-5.658-5.656a1.5 1.5 0 1 1 2.122-2.121L12 12.879l4.596-4.596a1.5 1.5 0 0 1 2.122 2.12l-5.657 5.658Z"
                />
              </g>
            </svg>
          </li>
          <li><a href="#">Recent Products</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">About</a></li>
        </ul>

        <div class="flex gap-4 text-white">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="1em"
            height="1em"
            viewBox="0 0 24 24"
          >
            <path
              fill="currentColor"
              fill-rule="evenodd"
              d="M14.385 15.446a6.751 6.751 0 1 1 1.06-1.06l5.156 5.155a.75.75 0 1 1-1.06 1.06zM6.46 13.884a5.25 5.25 0 1 1 7.43-.005l-.005.005l-.005.004a5.25 5.25 0 0 1-7.42-.004"
              clip-rule="evenodd"
            />
          </svg>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="1em"
            height="1em"
            viewBox="0 0 24 24"
          >
            <path
              fill="currentColor"
              d="M12 4a4 4 0 0 1 4 4a4 4 0 0 1-4 4a4 4 0 0 1-4-4a4 4 0 0 1 4-4m0 10c4.42 0 8 1.79 8 4v2H4v-2c0-2.21 3.58-4 8-4"
            />
          </svg>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="1em"
            height="1em"
            viewBox="0 0 24 24"
          >
            <path
              fill="currentColor"
              d="M21.822 7.431A1 1 0 0 0 21 7H7.333L6.179 4.23A1.994 1.994 0 0 0 4.333 3H2v2h2.333l4.744 11.385A1 1 0 0 0 10 17h8c.417 0 .79-.259.937-.648l3-8a1 1 0 0 0-.115-.921"
            />
            <circle cx="10.5" cy="19.5" r="1.5" fill="currentColor" />
            <circle cx="17.5" cy="19.5" r="1.5" fill="currentColor" />
          </svg>
        </div>
      </nav>

      <div class="md:flex items-center justify-between py-24">
        <div>
          <h1
            class="lg:max-w-[520px] text-5xl lg:text-7xl font-bold text-white mb-5"
          >
            Discover Most Suitable Watches
          </h1>
          <p class="font-medium lg:max-w-[456px] lg:text-lg mb-10">
            Find the best, reliable, and cheap smart watches here. We focus on
            product quality. Here you can find smart watches of almost all
            brands. So why you are waiting? Just order now!
          </p>
          <form action="" class="relative">
            <img
              class="absolute max-w-52 lg:top-4 top-3 left-2"
              src="../assets/img/search.svg"
              alt=""
            />
            <input
              class="focus:outline-none lg:py-5 max-w-[400px] pl-10 pr-28 py-4 lg:pr-32 lg:pl-12 rounded-xl"
              type="text"
              placeholder="Find the best brands"
            />
            <button
              class="xl:right-[127px] lg:right-[45px] right-[20px] sm:right-[180px] md:right-[10px] lg:bottom-2 top-[7px] absolute bg-[#3858D6] text-white font-medium text-lg px-3 py-2 lg:px-4 lg:py-2.5 rounded-xl"
            >
              Search
            </button>
          </form>
        </div>
        <img class="max-lg:max-w-[300px]" src="../assets/img/soat.png" alt="" />
      </div>
    </div>
    <!-- 383638 -->
    <!-- 0B0B0B -->
  </header>
</template>

<script setup></script>

<style scoped></style>
