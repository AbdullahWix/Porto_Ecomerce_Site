<template>
  <div v-b-hover="handleHover" class="mb-4 shadow rounded">
    <!-- <img v-if="isHovered" class="card-img" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Vans"> -->
    <b-img v-if="isHovered" src="https://m.media-amazon.com/images/I/51rLKWfhEdL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:200px; object-fit: contain;" class="p-4"></b-img>
    <b-img v-else src="https://m.media-amazon.com/images/I/51tje7mBkkL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:200px; object-fit: contain;" class="p-4"></b-img>
    <!-- <img v-else style="transform: rotateY(180deg);" class="card-img" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Vans"> -->
    <!-- Overlay -->
    <div class="card-img-overlay d-flex justify-content-end">
      <a href="#" class="card-link text-danger like">
        <b-icon v-if="isHovered" animation="throb" icon="heart" font-scale="1" variant="danger"></b-icon>
      </a>
    </div>
    <div class="card-body px-3 py-2">
      <b-list-group>
        <b-list-group-item variant="none" class="card-subtitle px-0 pb-1 pt-0 d-flex justify-content-between align-items-center" style="font-size:10px; border:none; font-weight:bold; color:gray">
          DRESS,TROUSERS
          <b-badge variant="none">
            <b-icon icon="heart-fill" font-scale="1.75" variant="danger"></b-icon>
          </b-badge>
        </b-list-group-item>
      </b-list-group>

      <h6 class="card-subtitle pt-1" style="color:#666666">Black Ears</h6>
      <b-form-rating class="p-0 m-0" size="sm" no-border inline value="3.75" variant="secondary" style="font-size:12px;"></b-form-rating>
      <h6 class="pt-1 card-subtitle" style="font-weight:bold; color:#262626">$101.00 - $111.00</h6>
      <div class="my-2 d-flex justify-content-between align-items-center" style="gap:5px">
          <b-button v-if="isHovered" squared variant="primary" size="sm" style="font-weight:600; font-size:13px;">
            <b-icon icon="bag"></b-icon>
            Add To Card
          </b-button>

          <b-button v-else squared variant="dark" size="sm" style="font-weight:600; font-size:13px;">
            <b-icon icon="bag"></b-icon>
            Add To Card
          </b-button>


          <div v-if="isHovered" class="d-flex" style="gap:4px">
            <div class="bg-secondary px-2 py-1">
              <b-icon icon="heart" variant="white" style="font-weight:700"></b-icon>
            </div>

            <div v-b-modal.quickview variant="none" class="bg-secondary px-2 py-1">
              <b-icon icon="box-arrow-up-right" variant="white" style="font-weight:700"></b-icon>
            </div>
          </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
      return {
        isHovered: false
      }
    },
    methods: {
      handleHover(hovered) {
        this.isHovered = hovered
      }
  }
}
</script>

<style>
  /* .card:hover{
    -webkit-box-shadow: -1px 9px 40px -12px rgba(0,0,0,0.75);
    -moz-box-shadow: -1px 9px 40px -12px rgba(0,0,0,0.75) ;
    box-shadow: -1px 9px 48px -12px Orgba(0,0,0,0.75);
  } */
</style>
