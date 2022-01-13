<template>
  <div class="container d-none d-lg-block">
    <div class="text-center">
      <p class="h4 font-weight-bold text-dark">COMPONENT-2</p>
      <hr>
    </div>

    <div>
      <div class="border-bottom d-flex justify-content-between align-items-center">
        <div class="">
          <p class="mt-3 py-2 px-3 bg-warning font-weight-bold">BEST SELLERS</p>
        </div>

        <div class="d-flex justify-content-center" style="gap:5px">
          <div class="bg-dark text-white py-2 px-2">
            <svg xmlns="http://www.w3.org/2000/svg" style="width:20px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" />
            </svg>
          </div>

          <div class="bg-dark text-light py-2 px-2">
            <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
            </svg>
          </div>

        </div>
      </div>
    </div>

    <div>
      <b-row>
        <b-col v-for="pr in 4" :key="pr" cols="3">
          <div class="mb-4 shadow rounded">
            <mainCard/>
          </div>
        </b-col>
      </b-row>
    </div>
  </div>
</template>
