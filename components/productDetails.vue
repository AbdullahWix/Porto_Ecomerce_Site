<template>
  <b-container>
    <div class="mt-2">
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
            <h3 class="card-title">Casual Note Bag</h3>
            <b-form-rating class="p-0 m-0" size="sm" no-border inline value="4" variant="secondary" style="font-size:12px;"></b-form-rating><span>(1 Reviews )</span>

            <h6 class="mt-2 card-subtitle" style="font-weight:bold; color:#262626">$00.00</h6>

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
                <b-button class="py-2" squared variant="dark" size="sm" style="font-weight:bold;">
                  <b-icon icon="bag"></b-icon>
                  ADD TO CART
                </b-button>
            </div>

            <hr>

            <!-- contact information -->
            <div class="mt-4 d-flex justify-content-between align-items-center">
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
    <div>
      <b-tabs
        active-nav-item-class="border-top-0 border-left-0 border-right-0 font-weight-bold border-dark text-dark"
        active-tab-class=""
        content-class="mt-3"
        >
          <b-tab title="DESCRIPTION">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, sed cumque. Nisi explicabo quam quas voluptate earum distinctio provident quo quibusdam fuga commodi tempora sit, nemo dolorum praesentium perspiciatis eligendi natus culpa qui id. Vitae atque non doloremque, ipsa illo provident quod quisquam fugit qui iusto maxime pariatur dolorum quo natus deserunt temporibus reiciendis, debitis rerum? Non, quasi? Inventore, vero.</p>
            <b-list-group v-for="ind in 3" :key="ind" class="py-1 ml-5">
              <b-list-group-item class="p-0 d-flex justify-content-start align-items-center border-0">
                <b-badge variant="none">
                <svg xmlns="http://www.w3.org/2000/svg" style="width:20px; margin-right:5px; padding-top:4px" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7 4a1 1 0 11-2 0 1 1 0 012 0zm-1-9a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z" clip-rule="evenodd" />
                </svg>
                </b-badge>
                    Any Product types that you want - Simple, Configurable
              </b-list-group-item>
            </b-list-group>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit, repellat neque nobis voluptas autem asperiores nihil id fuga perspiciatis facere aperiam modi repudiandae dolorem vel aut nemo. Nostrum, praesentium! Quam!</p>
          </b-tab>
          <b-tab title="SIZE GUIDE">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, sed cumque. Nisi explicabo quam quas voluptate earum distinctio provident quo quibusdam fuga commodi tempora sit, nemo dolorum praesentium perspiciatis eligendi natus culpa qui id. Vitae atque non doloremque, ipsa illo provident quod quisquam fugit qui iusto maxime pariatur dolorum quo natus deserunt temporibus reiciendis, debitis rerum? Non, quasi? Inventore, vero.</p>
            <b-list-group v-for="ind in 3" :key="ind" class="py-1 ml-5">
              <b-list-group-item class="p-0 d-flex justify-content-start align-items-center border-0">
                <b-badge variant="none">
                <svg xmlns="http://www.w3.org/2000/svg" style="width:20px; margin-right:5px; padding-top:4px" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7 4a1 1 0 11-2 0 1 1 0 012 0zm-1-9a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z" clip-rule="evenodd" />
                </svg>
                </b-badge>
                    Any Product types that you want - Simple, Configurable
              </b-list-group-item>
            </b-list-group>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit, repellat neque nobis voluptas autem asperiores nihil id fuga perspiciatis facere aperiam modi repudiandae dolorem vel aut nemo. Nostrum, praesentium! Quam!</p>
          </b-tab>
          <b-tab title="ADDITIONAL INFORMATION">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus, sed cumque. Nisi explicabo quam quas voluptate earum distinctio provident quo quibusdam fuga commodi tempora sit, nemo dolorum praesentium perspiciatis eligendi natus culpa qui id. Vitae atque non doloremque, ipsa illo provident quod quisquam fugit qui iusto maxime pariatur dolorum quo natus deserunt temporibus reiciendis, debitis rerum? Non, quasi? Inventore, vero.</p>
            <b-list-group v-for="ind in 3" :key="ind" class="py-1 ml-5">
              <b-list-group-item class="p-0 d-flex justify-content-start align-items-center border-0">
                <b-badge variant="none">
                <svg xmlns="http://www.w3.org/2000/svg" style="width:20px; margin-right:5px; padding-top:4px" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7 4a1 1 0 11-2 0 1 1 0 012 0zm-1-9a1 1 0 00-1 1v4a1 1 0 102 0V6a1 1 0 00-1-1z" clip-rule="evenodd" />
                </svg>
                </b-badge>
                    Any Product types that you want - Simple, Configurable
              </b-list-group-item>
            </b-list-group>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit, repellat neque nobis voluptas autem asperiores nihil id fuga perspiciatis facere aperiam modi repudiandae dolorem vel aut nemo. Nostrum, praesentium! Quam!</p>
          </b-tab>
          <b-tab title="REVIEWS(1)" active>
            <div class="d-flex align-items-start">
              <img class="mr-5" style="width:100px; height:100px;" src="http://placekitten.com/300/300" alt="">

              <div class="px-3 d-flex justify-content-between align-items-center bg-light" style="height:100px; width:100%">
                <div>
                  <p class="font-weight-bold text-dark m-0">Joe Doe - <span class="font-weight-normal text-gray">April 12,2018</span></p>
                  <p class="text-secondary pt-2" style="font-size:14px; font-weight:500;">Excelent</p>
                </div>
                <div>
                  <b-form-rating class="border-0 bg-light" size="sm" inline value="4"></b-form-rating>
                </div>
              </div>
            </div>

            <hr>

            <div class="mt-5">
              <p style="font-size:20px; font-weight:500; color:gray;">Add a review</p>
              <div class="bg-light p-4">
                <p class="font-weight-bold m-0">Your rating *</p>
                <b-form-rating class="px-0 pt-2 border-0 bg-light" size="sm" inline value="0"></b-form-rating>
                <!-- Review -->
                <div>
                  <p class="font-weight-bold m-0 pt-2">Your review *</p>
                  <div class="mt-2">
                    <b-form-textarea
                      id="textarea"
                      v-model="text"
                      rows="4"
                      max-rows="8"
                    ></b-form-textarea>
                  </div>
                </div>

                <!-- Name -->
                <div>
                  <p class="font-weight-bold m-0 pt-2">Name *</p>
                  <div class="mt-2">
                    <b-form-input v-model="text"></b-form-input>
                  </div>
                </div>

                <!-- Email -->
                <div>
                  <p class="font-weight-bold m-0 pt-2">Email *</p>
                  <div class="mt-2">
                    <b-form-input v-model="text"></b-form-input>
                  </div>
                </div>

                <div class="mt-3">
                  <b-form-checkbox value="me">
                    <p class="font-weight-bold text-secondary">Save my name, email, and website in this browser for the next time i comment.</p>
                  </b-form-checkbox>
                </div>

                <div class="mt-4">
                  <b-button squared variant="primary">Submit</b-button>
                </div>
              </div>
            </div>
          </b-tab>
      </b-tabs>
    </div>
  </b-container>
</template>
