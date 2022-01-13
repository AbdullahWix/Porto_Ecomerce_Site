<template>
  <div style="height:700px">
    <div class="text-center">
      <p class=" h4 font-weight-bold text-dark">COMPONENT-1</p>
      <hr>
    </div>
    <!-- Component Categories Section -->
    <div class="position-relative mb-5 container">
      <div class="d-flex justify-content-between align-items-center bg-primary" style="height:275px; width:100%">
        <div class="bg-dark text-white py-3 px-4" style="height:60px">
          <svg xmlns="http://www.w3.org/2000/svg" style="width:20px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" />
          </svg>
        </div>

        <div class="mx-5">
          <div class="d-flex" style="gap:20px">
            <div>
              <div class="d-flex justify-content-center align-items-center bg-white rounded-circle" style="width:90px; height:90px;">
                <b-img rounded="circle" src="https://s-media-cache-ak0.pinimg.com/236x/3b/36/ca/3b36ca3afe0fa0fd4984b9eee2e154bb.jpg" style="width:60px; height:60px;" alt="Circle image"></b-img>
              </div>
              <p class="text-center h6 pt-2 text-white">Mobiles</p>
            </div>

            <div>
              <div class="d-flex justify-content-center align-items-center bg-white rounded-circle" style="width:90px; height:90px;">
                <b-img rounded="circle" src="https://s-media-cache-ak0.pinimg.com/236x/3b/36/ca/3b36ca3afe0fa0fd4984b9eee2e154bb.jpg" style="width:60px; height:60px;" alt="Circle image"></b-img>
              </div>
              <p class="text-center h6 pt-2 text-white">Television</p>
            </div>

            <div>
              <div class="d-flex justify-content-center align-items-center bg-white rounded-circle" style="width:90px; height:90px;">
                <b-img rounded="circle" src="https://s-media-cache-ak0.pinimg.com/236x/3b/36/ca/3b36ca3afe0fa0fd4984b9eee2e154bb.jpg" style="width:60px; height:60px;" alt="Circle image"></b-img>
              </div>
              <p class="text-center h6 pt-2 text-white">Cameras</p>
            </div>

            <div>
              <div class="d-flex justify-content-center align-items-center bg-white rounded-circle" style="width:90px; height:90px;">
                <b-img rounded="circle" src="https://s-media-cache-ak0.pinimg.com/236x/3b/36/ca/3b36ca3afe0fa0fd4984b9eee2e154bb.jpg" style="width:60px; height:60px;" alt="Circle image"></b-img>
              </div>
              <p class="text-center h6 pt-2 text-white">Speakers</p>
            </div>

            <div>
              <div class="d-flex justify-content-center align-items-center bg-white rounded-circle" style="width:90px; height:90px;">
                <b-img rounded="circle" src="https://s-media-cache-ak0.pinimg.com/236x/3b/36/ca/3b36ca3afe0fa0fd4984b9eee2e154bb.jpg" style="width:60px; height:60px;" alt="Circle image"></b-img>
              </div>
              <p class="text-center h6 pt-2 text-white">Laptops</p>
            </div>

            <div>
              <div class="d-flex justify-content-center align-items-center bg-white rounded-circle" style="width:90px; height:90px;">
                <b-img rounded="circle" src="https://s-media-cache-ak0.pinimg.com/236x/3b/36/ca/3b36ca3afe0fa0fd4984b9eee2e154bb.jpg" style="width:60px; height:60px;" alt="Circle image"></b-img>
              </div>
              <p class="text-center h6 pt-2 text-white">Watches</p>
            </div>

            <div>
              <div class="d-flex justify-content-center align-items-center bg-white rounded-circle" style="width:90px; height:90px;">
                <b-img rounded="circle" src="https://s-media-cache-ak0.pinimg.com/236x/3b/36/ca/3b36ca3afe0fa0fd4984b9eee2e154bb.jpg" style="width:60px; height:60px;" alt="Circle image"></b-img>
              </div>
              <p class="text-center h6 pt-2 text-white">Refrigerator</p>
            </div>

            <div>
              <div class="d-flex justify-content-center align-items-center bg-white rounded-circle" style="width:90px; height:90px;">
                <b-img rounded="circle" src="https://s-media-cache-ak0.pinimg.com/236x/3b/36/ca/3b36ca3afe0fa0fd4984b9eee2e154bb.jpg" style="width:60px; height:60px;" alt="Circle image"></b-img>
              </div>
              <p class="text-center h6 pt-2 text-white">Mixer</p>
            </div>
          </div>
        </div>

        <div class="bg-dark text-light py-3 px-4" style="height:60px">
          <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
          </svg>
        </div>
      </div>

      <div class="position-absolute" style="top:215px;left:60px; right:60px">
        <!-- Component Product Section -->
        <div class="d-flex justify-content-between">
          <div class="bg-dark text-white py-3 px-4" style="height:60px">
            <svg xmlns="http://www.w3.org/2000/svg" style="width:20px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7" />
            </svg>
          </div>

          <!-- Carrocel Start Here...-->
          <!-- <VueSlickCarousel v-bind="setting"> -->
            <b-row>
              <b-col v-for="i in 3" :key="i" class="m-2">
                <div class="mb-4 shadow">
                  <!-- <img class="card-img" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Vans"> -->
                    <b-img src="https://m.media-amazon.com/images/I/51tje7mBkkL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:200px; object-fit: contain;" class="p-4"></b-img>
                  <!-- Overlay -->
                  <div class="card-img-overlay d-flex justify-content-end">
                    <a href="#" class="card-link text-danger like">
                      <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                      </svg>
                    </a>
                  </div>

                  <div class="card-body">
                    <p class="card-subtitle pt-1 font-weight-bold" style="color:#666666; font-size:14px">Lorem ipsum, dolor sit amet consectetur</p>
                    <p class="border-bottom card-subtitle py-2 font-weight-bold" style="color:#D0D0D0; font-size:10px">ORGANIC</p>

                    <div class="d-flex justify-content-between align-items-center">
                      <div>
                        <b-form-rating class="p-0 m-0" size="sm" no-border inline value="3.75" variant="secondary" style="font-size:10px;"></b-form-rating>
                        <p class="pl-1 text-danger card-subtitle font-weight-bold" style="font-size:12px">$101.00</p>
                      </div>
                      <div class="mt-1">
                        <b-avatar>
                          <svg class="opacity-100" xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" />
                          </svg>
                        </b-avatar>
                      </div>
                    </div>
                  </div>
                </div>
              </b-col>
            </b-row>
          <!-- </VueSlickCarousel> -->



          <div class="bg-dark text-light py-3 px-4" style="height:60px">
            <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
            </svg>
          </div>
        </div>
      </div>
    </div>


  </div>
</template>
<script>
  // import VueSlickCarousel from 'vue-slick-carousel'
  // import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  // import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'

  export default {
    // components: { VueSlickCarousel },
    // data(){
    //   return {
    //     setting:{
    //       "dots": true,
    //       "focusOnSelect": true,
    //       "infinite": true,
    //       "speed": 5000,
    //       "slidesToShow": 3,
    //       "slidesToScroll": 3,
    //       "touchThreshold": 5,
    //     }
    //   }
    // }
  }
</script>
