<template>
  <div v-b-hover="handleHover">
    <div class="mb-4 shadow rounded">
      <b-img v-if="isHovered" src="https://m.media-amazon.com/images/I/51rLKWfhEdL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:200px; object-fit: contain;" class="p-4"></b-img>
      <b-img v-else src="https://m.media-amazon.com/images/I/51tje7mBkkL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:200px; object-fit: contain;" class="p-4"></b-img>

      <!-- Overlay -->
      <div v-if="isHovered" class="card-img-overlay d-flex justify-content-center align-items-center">
        <div class="d-flex" style="gap:3px;">
          <b-avatar class="bg-primary">
            <b-icon icon="search" scale="1"></b-icon>
          </b-avatar>

          <b-avatar class="bg-primary">
            <b-icon icon="heart" scale="1"></b-icon>
          </b-avatar>

          <b-avatar class="bg-primary">
            <b-icon icon="star" scale="1"></b-icon>
          </b-avatar>
        </div>
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
            <b-avatar v-if="isHovered" class="bg-danger">
              <b-icon icon="cart-dash" scale="1.25"></b-icon>
            </b-avatar>
            <b-avatar v-else>
              <b-icon icon="cart-dash" scale="1.25"></b-icon>
            </b-avatar>
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
