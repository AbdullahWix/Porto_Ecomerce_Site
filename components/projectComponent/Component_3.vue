<template>
  <div class="container mt-5">
    <div class="text-center">
      <p class=" h4 font-weight-bold text-dark">COMPONENT-3</p>
      <hr>
    </div>

    <b-tabs
        active-nav-item-class="rounded-0 border-top-0 border-left-0 border-right-0 font-weight-bold border-dark text-white"
        active-tab-class=""
        content-class="mt-3 font-weight-bold"
        justified
        pills
        >
        <b-tab title="HOT PRODUCT" active>
          <div>
            <b-row>
              <b-col v-for="pr in 4" :key="pr" cols="3">
                <div class="mb-4 shadow rounded">
                  <img class="card-img" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Vans">
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
          </div>
        </b-tab>

        <b-tab title="NEW ARRIVALS">
          <div>
            <b-row>
              <b-col v-for="pr in 4" :key="pr" cols="3">
                <div class="mb-4 shadow rounded">
                  <img class="card-img" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Vans">
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
          </div>
        </b-tab>

        <b-tab title="TODAYS DEALS">
          <div>
            <b-row>
              <b-col v-for="pr in 4" :key="pr" cols="3">
                <div class="mb-4 shadow rounded">
                  <img class="card-img" src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" alt="Vans">
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
          </div>
        </b-tab>

    </b-tabs>
  </div>
</template>
