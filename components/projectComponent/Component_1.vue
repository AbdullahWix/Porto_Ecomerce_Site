<template>
  <div class="d-none d-lg-block" style="height:700px">
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
            <div v-for="item in categories" :key="item">
              <div class="d-flex justify-content-center align-items-center bg-white rounded-circle" style="width:90px; height:90px;">
                <b-img :src="item.img" fluid-grow alt="Responsive image" style="width:100%; height:45px; object-fit: contain;"></b-img>
              </div>
              <p class="text-center h6 pt-2 text-white">{{item.name}}</p>
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
            <b-row class="z-index">
              <b-col v-for="i in 3" :key="i" class="m-2">
                <mainCard class="bg-white rounded"/>
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
  export default {
    data(){
      return{
        categories:[
          {
            img:'https://m.media-amazon.com/images/I/61O45C5qASL._AC_SY355_.jpg',
            name:'Mobile',
            avilable:4
          },
          {
            img:'https://m.media-amazon.com/images/I/91CXxVtVkAL._AC_UY327_FMwebp_QL65_.jpg',
            name:'Telivition',
            avilable:10
          },
          {
            img:'https://m.media-amazon.com/images/I/61eIrd0D6DL._AC_SY355_.jpg',
            name:'Cameras',
            avilable:10
          },
          {
            img:'https://m.media-amazon.com/images/I/71qj8jgS6qL._AC_UL480_QL65_.jpg',
            name:'Speakers',
            avilable:10
          },
          {
            img:'https://m.media-amazon.com/images/I/71d5rAq4YaL._AC_UY327_FMwebp_QL65_.jpg',
            name:'Laptops',
            avilable:3
          },
          {
            img:'https://m.media-amazon.com/images/I/71DP0v5VqhL._AC_UY327_FMwebp_QL65_.jpg',
            name:'Watches',
            avilable:10
          },
          {
            img:'https://m.media-amazon.com/images/I/71hhiKGR-zL._AC_UL480_FMwebp_QL65_.jpg',
            name:'Refrigerator',
            avilable:15
          },
          {
            img:'https://m.media-amazon.com/images/I/61TbMV5bQqL._AC_UY327_FMwebp_QL65_.jpg',
            name:'Mixer',
            avilable:7
          }
        ]
      }
    }
  }
</script>
