<template>
<div class="px-1">
  <b-list-group style="max-width: 300px;">
    <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
      <span class="mr-auto h6">PRODUCTS</span>
      <b-badge variant="none">
        <svg xmlns="http://www.w3.org/2000/svg" style="width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg>
      </b-badge>
    </b-list-group-item>
  </b-list-group>

  <b-list-group style="max-width: 300px;">
    <div @click="layoutdrop">
      <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="" style="cursor: pointer; user-select: none;">
        <span class="mr-auto h6">PAGES</span>
        <b-badge variant="none">
          <svg v-if="!layoutShow" xmlns="http://www.w3.org/2000/svg" style="width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
          </svg>

          <svg v-else xmlns="http://www.w3.org/2000/svg" style="width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
          </svg>
        </b-badge>
      </b-list-group-item>
    </div>
    <div v-if="layoutShow">
      <b-list-group-item class="bg-dark text-light border-0">
        <span class="pl-4">Wishlist</span>
      </b-list-group-item>
      <b-list-group-item class="bg-dark text-light border-0">
        <span class="pl-4">Shopping Cart</span>
      </b-list-group-item>
      <b-list-group-item class="bg-dark text-light border-0">
        <span class="pl-4">Checkout</span>
      </b-list-group-item>
      <b-list-group-item class="bg-dark text-light border-0">
        <span class="pl-4">Dashboard</span>
      </b-list-group-item>
      <b-list-group-item class="bg-dark text-light border-0">
        <span class="pl-4">Contact Us</span>
      </b-list-group-item>
      <b-list-group-item class="bg-dark text-light border-0">
        <span class="pl-4">Login</span>
      </b-list-group-item>
      <b-list-group-item class="bg-dark text-light border-0">
        <span class="pl-4">Forgot Password</span>
      </b-list-group-item>
    </div>
  </b-list-group>

  <b-list-group style="max-width: 300px;">
    <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
      <span class="mr-auto h6">BLOG</span>
    </b-list-group-item>
  </b-list-group>

  <b-list-group style="max-width: 300px;">
    <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
      <span class="mr-auto h6">ABOUT US</span>
    </b-list-group-item>
  </b-list-group>

  <div class="mt-2">
    <b-list-group style="max-width: 300px;">
      <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
        <span class="mr-auto h6">SPECIAL OFFER!</span>
      </b-list-group-item>
    </b-list-group>

    <b-list-group style="max-width: 300px;">
      <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
        <span class="mr-auto h6">BUY PORTO</span>
      </b-list-group-item>
    </b-list-group>
  </div>

  <div class="mt-2">
    <b-list-group style="max-width: 300px;">
      <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
        <span class="mr-auto h6">MY ACCOUNT</span>
      </b-list-group-item>
    </b-list-group>

    <b-list-group style="max-width: 300px;">
      <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
        <span class="mr-auto h6">CONTACT US</span>
      </b-list-group-item>
    </b-list-group>
  </div>

  <div class="mt-2">
    <b-list-group style="max-width: 300px;">
      <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
        <span class="mr-auto h6">BLOG</span>
      </b-list-group-item>
    </b-list-group>
  </div>

  <div class="mt-2">
    <b-list-group style="max-width: 300px;">
      <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
        <span class="mr-auto h6">MY WISHLIST</span>
      </b-list-group-item>
    </b-list-group>
  </div>

  <div class="mt-2">
    <b-list-group style="max-width: 300px;">
      <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
        <span class="mr-auto h6">CART</span>
      </b-list-group-item>
    </b-list-group>
  </div>
  <div class="mt-2">
    <b-list-group style="max-width: 300px;">
      <b-list-group-item class="bg-dark text-light border-0 d-flex align-items-center" variant="">
        <span class="mr-auto h6">LOG IN</span>
      </b-list-group-item>
    </b-list-group>
  </div>

  <!-- Search bar Start here -->
  <b-navbar-nav>
    <b-form class="form-inline mr-sm-3 ml-3">
      <b-form-group>
        <b-input-group class="input-group-alternative input-group-merge">
          <b-form-input variant="primary" placeholder="Search..." type="text" style="color:#808080; opacity:.75;border-radius: 25px 0px 0px 25px;"></b-form-input>
          <div class="input-group-append" style="">
            <span class="input-group-text" style="background-color:white; border-left:none; opacity:.75;border-radius: 0px 25px 25px 0px;">
              <svg xmlns="http://www.w3.org/2000/svg" style="height:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
              </svg>
            </span>
          </div>
        </b-input-group>
      </b-form-group>
    </b-form>
  </b-navbar-nav>
  <!-- Search bar End here -->


</div>
</template>
<script>
export default {
  name: 'SidebarMenu',
  data(){
    return{
      layoutShow:false
    }
  },
  methods:{
    layoutdrop(){
      this.layoutShow = !this.layoutShow;
    },
  }
}
</script>
