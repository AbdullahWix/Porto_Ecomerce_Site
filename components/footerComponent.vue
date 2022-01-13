<template>
  <div class="my-5">
    <div>
      <h1 class="text-center my-5">Footer</h1>
    </div>
    <b-container class="bv-example-row">
      <b-row>
        <!-- Left Side -->
        <b-col cols="12" sm="6" md="4" lg="3">
          <div>
            <h6 class="font-weight-bold">CONTACT INFO</h6>
            <div class="mt-3">
              <p class="font-weight-bold m-0" style="font-size:14px;color:gray">ADDRESS:</p>
              <p class="font-weight-bold m-0 pt-1" style="font-size:12px; color:#B1B1B1">123 Street Name, City, England</p>
            </div>
            <div class="mt-2">
              <p class="font-weight-bold m-0" style="font-size:14px;color:gray">PHONE:</p>
              <p class="font-weight-bold m-0 pt-1" style="font-size:12px; color:#B1B1B1">(123) 4673963556</p>
            </div>
            <div class="mt-2">
              <p class="font-weight-bold m-0" style="font-size:14px;color:gray">EMAIL:</p>
              <p class="font-weight-bold m-0 pt-1" style="font-size:12px; color:#B1B1B1">mail.@example.com</p>
            </div>
            <div class="mt-2">
              <p class="font-weight-bold m-0" style="font-size:14px;color:gray">WORKING DAYS/HOURS:</p>
              <p class="font-weight-bold m-0 pt-1" style="font-size:12px; color:#B1B1B1">Mon - Sun / 9:00AM - 8:00PM</p>
            </div>
          </div>
        </b-col>

        <!-- Right Side -->
        <b-col cols="12" sm="6" md="8" lg="9">
          <div>
            <b-row>
              <b-col cols="12" lg="6" class="my-2">
                <div>
                  <h6 class="font-weight-bold">SUBSCRIBE NEWSLETTER</h6>
                  <div class="mt-2">
                    <p class="font-weight-bold m-0 pt-1" style="font-size:14px; color:#B1B1B1">Get all the lasted information on Events. Sales and Offers.
                    Sign up for newsletter today.</p>
                  </div>
                </div>
              </b-col>

              <b-col cols="12" lg="6" class="my-2">
                <div>
                  <b-navbar-nav>
                    <b-form class="navbar-search form-inline mr-sm-3 ml-lg-5">
                      <b-form-group class="mb-0">
                        <b-input-group class="input-group-alternative input-group-merge">
                          <b-form-input variant="primary" placeholder="Search..." type="text" style="height:40px;color:#808080; opacity:.75;border-radius: 25px 0px 0px 25px;"></b-form-input>

                          <div class="input-group-append" style="">
                            <!--
                              <b-button class="m-0 py-1 " squared variant="primary">Button</b-button>
                            </span> -->
                            <div class="d-flex justify-content-center align-items-center border px-3 bg-primary" style="height:40px;color:#808080; opacity:.75;border-radius: 0px 25px 25px 0px;">
                              <button class="text-center border-0 bg-primary text-white font-weight-bold" href="">Subscribe</button>
                            </div>

                          </div>
                        </b-input-group>
                      </b-form-group>
                    </b-form>
                  </b-navbar-nav>
                </div>
              </b-col>
            </b-row>
          </div>

          <hr>

          <div>
            <b-row>
              <b-col cols="12" md="6" lg="3">
                <div>
                  <h6 class="font-weight-bold">CUSTOMER SERVICE</h6>
                  <div>
                    <div class="pt-1"><b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">About Us</b-link></div>
                    <div class="pt-2">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">Contact Us</b-link>
                    </div>
                    <div class="pt-2">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">My Account</b-link>
                    </div>
                  </div>
                </div>
              </b-col>

              <b-col cols="12" md="6" lg="3">
                <div class="mt-4">
                    <div class="pt-2">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">Order History</b-link>
                    </div>
                    <div class="pt-2">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">Advance Search</b-link>
                    </div>
                    <div class="pt-2">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">Login</b-link>
                    </div>
                  </div>
              </b-col>

              <b-col cols="12" md="6" lg="3">
                <div>
                  <h6 class="font-weight-bold">About Us</h6>
                  <div>
                    <div class="pt-1">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">Super Fast Vue Theme</b-link>
                    </div>
                    <div class="pt-2">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">1st Fully working ajax Theme</b-link>
                    </div>
                    <div class="pt-2">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">33 Unique Shop Layout</b-link>
                    </div>
                  </div>
                </div>
              </b-col>

              <b-col cols="12" md="6" lg="3">
                <div class="mt-4">
                    <div class="pt-2">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray">Powerful Admin Panel</b-link>
                    </div>
                    <div class="pt-2">
                      <b-link class="font-weight-bold m-0" style="font-size:14px;color:gray" href="#foo">Mobile & Retina Optimized</b-link>
                    </div>
                  </div>
              </b-col>
            </b-row>
          </div>
        </b-col>
      </b-row>
    </b-container>
    <hr>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>
