<template>
  <div>
    <b-card no-body class="overflow-hidden mb-4 p-2" style="border:none;">
      <b-row no-gutters>
        <b-col v-b-hover="handleHover" cols="5" lg="4">
          <!-- <img class="card-img" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Vans"> -->
          <b-img v-if="isHovered" src="https://m.media-amazon.com/images/I/51rLKWfhEdL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:200px; object-fit: contain;" class="p-2"></b-img>
          <b-img v-else src="https://m.media-amazon.com/images/I/51tje7mBkkL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:200px; object-fit: contain;" class="p-2"></b-img>
        </b-col>
        <b-col>
          <div class="px-4">
            <p class="card-title m-0 font-weight-bold text-dark" style="font-size:14px;">COM,HEADPHONE</p>
            <p class="card-subtitle mt-1" style="color:#666666; font-size:14px; font-weight:600;">Black Ears</p>
            <b-form-rating class="p-0 m-0" size="sm" no-border inline value="4" variant="secondary" style="font-size:12px;"></b-form-rating>

            <p class="card-subtitle pt-1" style="color:#666666; font-size:15px;">
              This is a wider card with supporting text as a natural lead-in to additional content.
              This content is a little bit longer.
            </p>
            <h6 class="mt-2 card-subtitle" style="font-weight:bold; color:#262626">$259.00 <span>$290.00</span></h6>

            <div class="mt-2 d-flex align-items-center" style="gap:15px">
                <b-button squared variant="dark" size="sm" style="font-weight:bold;">Add To Card</b-button>

                <!-- <svg xmlns="http://www.w3.org/2000/svg" style="width:20px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                </svg> -->
                <b-icon icon="heart" font-scale="1.25" style="font-weight:700"></b-icon>

                <div v-b-modal.quickview variant="none" class="pb-2">
                  <b-icon icon="box-arrow-up-right" font-scale="1.25" style="font-weight:700"></b-icon>
                </div>
            </div>
          </div>

          <!-- Quick Modal Start Here -->
          <b-modal id="quickview" size="xl" centered>
            <!-- Modal Body section -->
            <div>
              <b-row>
                <b-col>
                  <!-- <b-card-img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Image" class="rounded-0" style="height:auto; boeder:none"></b-card-img> -->
                  <b-img src="https://m.media-amazon.com/images/I/51tje7mBkkL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:400px; object-fit: contain;" class="p-4"></b-img>
                  <div class="mt-3 d-flex justify-content-between mb-3">
                    <div>
                      <!-- <img style="width:100px;height:100px; border-style:solid;" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt=""> -->
                      <b-img src="https://m.media-amazon.com/images/I/51tje7mBkkL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:175px; object-fit: contain; border: solid 2px; " class="p-2"></b-img>
                    </div>
                    <div>
                      <b-img src="https://m.media-amazon.com/images/I/51tje7mBkkL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:175px; object-fit: contain;" class="p-2"></b-img>
                    </div>
                    <div>
                      <b-img src="https://m.media-amazon.com/images/I/51tje7mBkkL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:175px; object-fit: contain;" class="p-2"></b-img>
                    </div>
                    <div>
                      <b-img src="https://m.media-amazon.com/images/I/51tje7mBkkL._AC_SX425_.jpg" fluid-grow alt="Responsive image" style="width:100%; height:175px; object-fit: contain;" class="p-2"></b-img>
                    </div>
                  </div>
                </b-col>
                <b-col>
                  <div class="px-4">
                    <h3 class="card-title mt-4">Casual Note Bag</h3>
                    <b-form-rating class="p-0 mt-2" size="sm" no-border inline value="4" variant="secondary" style="font-size:12px;"></b-form-rating><span>(1 Reviews )</span>

                    <h6 class="mt-3 card-subtitle" style="font-weight:bold; color:#262626">$259.00</h6>

                    <p class="my-3 card-subtitle" style="color:#666666">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tenetur odit illo consectetur velit a pariatur laboriosam perspiciatis ducimus voluptatum, quis placeat accusantium maiores dolorem officiis assumenda porro nihil, modi facere ipsam fugit praesentium fuga qui doloremque ullam. At nihil assumenda ratione aut, architecto totam sunt!
                    </p>
                    <small class="font-weight-bold pt-3">SKU: <span class="font-weight-normal">98561236458</span></small>
                    <br>

                    <small class="font-weight-bold">CATEGORIES: <span class="font-weight-normal">COM, T-SHIRT, CLOTHING,SHOES</span></small>
                    <br>
                    <small class="font-weight-bold">TAGS: <span class="font-weight-normal">HUB, SPORS, FASHION</span></small>

                    <hr>

                    <div class="mt-2 d-flex align-items-center" style="gap:15px">
                        <b-form-spinbutton id="sb-inline" value="1" inline></b-form-spinbutton>
                        <b-button squared variant="dark" size="sm" style="font-weight:bold;">
                          <svg xmlns="http://www.w3.org/2000/svg" style="width:20px; color:white; margin-bottom:5px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
                          </svg>
                          ADD TO CART
                        </b-button>
                    </div>

                    <hr>

                    <!-- contact information -->
                    <div class="mt-5 d-flex justify-content-between align-items-center">
                      <div class="d-flex align-items-center" style="gap:10px">
                        <div class="rounded-circle" style="padding:6px 10px; border: solid 2px; border-color:#D3D3D3">
                          <b-icon icon="facebook"></b-icon>
                        </div>

                        <div class="rounded-circle" style="padding:6px 10px; border: solid 2px; border-color:#D3D3D3">
                          <b-icon icon="twitter"></b-icon>
                        </div>

                        <div class="rounded-circle" style="padding:6px 10px; border: solid 2px; border-color:#D3D3D3">
                          <b-icon icon="linkedin"></b-icon>
                        </div>

                        <div class="rounded-circle" style="padding:6px 10px; border: solid 2px; border-color:#D3D3D3">
                          <b-icon icon="google"></b-icon>
                        </div>

                        <div class="rounded-circle" style="padding:6px 10px; border: solid 2px; border-color:#D3D3D3">
                          <b-icon icon="envelope-open-fill"></b-icon>
                        </div>

                      </div>

                      <div>
                        <b-button class="py-2" squared variant="none" size="sm" style="font-weight:bold;">
                          <b-icon icon="heart"></b-icon>
                          ADD TO WISHLIST
                        </b-button>
                      </div>
                    </div>

                  </div>
                </b-col>
              </b-row>
            </div>

            <template #modal-footer>
              <p></p>
            </template>
          </b-modal>
          <!-- Quick Modal End Here -->
        </b-col>
      </b-row>
    </b-card>
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
