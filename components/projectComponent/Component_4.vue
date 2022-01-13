<template>
  <div class="container my-5 d-none d-lg-block">
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
          <div v-for="item in categories" :key="item">
            <div class="d-flex justify-content-center align-items-center bg-light cardbg">
              <b-img :src="item.img" fluid-grow alt="Responsive image" style="width:100%; height:125px; object-fit: contain;" class="p-4"></b-img>
            </div>
            <div class="pt-2">
              <p class="m-0 text-center font-weight-bold">{{item.name}}</p>
              <p class="text-center" style="font-size:12px; color:gray; font-weight:500">{{item.avilable}} PRODUCTS</p>
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
          img:'https://m.media-amazon.com/images/I/71d5rAq4YaL._AC_UY327_FMwebp_QL65_.jpg',
          name:'Laptop',
          avilable:3
        },
        {
          img:'https://m.media-amazon.com/images/I/61TbMV5bQqL._AC_UY327_FMwebp_QL65_.jpg',
          name:'Mixer',
          avilable:7
        },
        {
          img:'https://m.media-amazon.com/images/I/915Xj2rO8WL._AC_UY327_FMwebp_QL65_.jpg',
          name:'Telivition',
          avilable:10
        },
      ]
    }
  }
}
</script>


<style scoped>
  .cardbg{
    width:200px;
    height:150px;
    border-top-left-radius: 9999px;
    border-top-right-radius: 9999px;
  }
</style>
