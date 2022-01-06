<template>
  <b-container>
    <div class="mt-5">
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
    <div>
      <b-tabs
        active-nav-item-class="border-top-0 border-left-0 border-right-0 font-weight-bold border-dark text-dark"
        active-tab-class=""
        content-class="mt-3"
        >
          <b-tab title="DESCRIPTION" active>
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
          <b-tab title="REVIEWS(1)">
            <div class="d-flex align-items-start">
              <img class="mr-5" style="width:100px; height:100px;" src="http://placekitten.com/300/300" alt="">

              <div class="px-3 d-flex justify-content-between align-items-center bg-light" style="height:100px; width:100%">
                <div>
                  <p class="font-weight-bold text-dark">Joe Doe - <span class="font-weight-normal text-gray">April 12,2018</span></p>
                  <p>Excelent</p>
                </div>
                <div>
                  <b-form-rating class="border-0" size="sm" inline value="4"></b-form-rating>
                </div>
              </div>
            </div>
          </b-tab>
      </b-tabs>
    </div>
  </b-container>
</template>
