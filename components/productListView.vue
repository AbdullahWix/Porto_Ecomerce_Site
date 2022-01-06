<template>
  <div>
    <b-card no-body class="overflow-hidden mb-4" style="max-width: 100%; max-height:250px; border:none;">
      <b-row no-gutters>
        <b-col md="4">
          <b-card-img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Image" class="rounded-0" style="height:200px"></b-card-img>
        </b-col>
        <b-col>
          <div class="px-4">
            <p class="card-title">COM,HEADPHONE</p>
            <h6 class="card-subtitle" style="color:#666666">Black Ears</h6>
            <b-form-rating class="p-0 m-0" size="sm" no-border inline value="4" variant="secondary" style="font-size:12px;"></b-form-rating>

            <p class="mt-1 card-subtitle" style="color:#666666">
              This is a wider card with supporting text as a natural lead-in to additional content.
              This content is a little bit longer.
            </p>
            <h6 class="mt-2 card-subtitle" style="font-weight:bold; color:#262626">$259.00 <span>$290.00</span></h6>

            <div class="mt-2 d-flex align-items-center" style="gap:15px">
                <b-button squared variant="dark" size="sm" style="font-weight:bold;">Add To Card</b-button>

                <svg xmlns="http://www.w3.org/2000/svg" style="width:20px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                </svg>

                <div v-b-modal.quickview variant="none" class="pb-2">
                  <svg xmlns="http://www.w3.org/2000/svg" style="width:20px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14" />
                  </svg>
                </div>
            </div>
          </div>

          <!-- Quick Modal Start Here -->
          <b-modal id="quickview" size="xl" centered style="border:none">
            <!-- Modal Body section -->
            <div class="p-5">
              <b-row>
                <b-col>
                  <b-card-img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Image" class="rounded-0" style="height:auto; boeder:none"></b-card-img>
                  <div class="mt-3 d-flex justify-content-between mb-3">
                    <div>
                      <img style="width:100px;height:100px; border-style:solid;" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="">
                    </div>
                    <div>
                      <img style="width:100px;height:100px;" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="">
                    </div>
                    <div>
                      <img style="width:100px;height:100px;" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="">
                    </div>
                    <div>
                      <img style="width:100px;height:100px;" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="">
                    </div>
                  </div>
                </b-col>
                <b-col>
                  <div class="px-4">
                    <h3 class="card-title">Casual Note Bag</h3>
                    <b-form-rating class="p-0 m-0" size="sm" no-border inline value="4" variant="secondary" style="font-size:12px;"></b-form-rating><span>(1 Reviews )</span>

                    <h6 class="mt-2 card-subtitle" style="font-weight:bold; color:#262626">$259.00</h6>

                    <p class="mt-1 card-subtitle" style="color:#666666">
                      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tenetur odit illo consectetur velit a pariatur laboriosam perspiciatis ducimus voluptatum, quis placeat accusantium maiores dolorem officiis assumenda porro nihil, modi facere ipsam fugit praesentium fuga qui doloremque ullam. At nihil assumenda ratione aut, architecto totam sunt!
                    </p>
                    <small class="font-weight-bold">SKU: <span class="font-weight-normal">98561236458</span></small>
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

                    <div>

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
