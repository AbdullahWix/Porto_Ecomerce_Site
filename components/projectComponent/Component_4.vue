<template>
  <div class="container my-5">
    <div class="text-center">
      <p class="h4 font-weight-bold text-dark">COMPONENT-4</p>
      <hr>
    </div>

    <div class="text-center">
      <p class="font-weight-bold text-dark">BROWES OUR CATEGORIES</p>
      <hr>
    </div>
    <!-- Featured Product Section -->
    <div class="pt-4 d-flex justify-content-between align-items-center">
      <div class="bg-secondary text-white py-2 px-3">
        <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18" />
        </svg>
      </div>

      <div>
        <div class="d-flex justify-content-center align-items-center" style="gap:20px">
          <div v-for="item in 4" :key="item">
            <div class="d-flex justify-content-center align-items-center bg-light cardbg">
              <b-img rounded="circle" src="https://s-media-cache-ak0.pinimg.com/236x/3b/36/ca/3b36ca3afe0fa0fd4984b9eee2e154bb.jpg" style="width:120px; height:120px;" alt="Circle image"></b-img>
            </div>
            <div class="pt-2">
              <p class="m-0 text-center font-weight-bold">DRESS</p>
              <p class="text-center" style="font-size:12px; color:gray; font-weight:500">3 PRODUCTS</p>
            </div>
          </div>
        </div>
      </div>

      <div class="bg-secondary text-light py-2 px-3">
        <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
        </svg>
      </div>
    </div>
  </div>
</template>
<style scoped>
  .cardbg{
    width:200px;
    height:150px;
    border-top-left-radius: 9999px;
    border-top-right-radius: 9999px;
  }
</style>
