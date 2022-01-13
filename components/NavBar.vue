<!-- Please remove this file from your project -->
<template>
  <div style="min-width:540px">
    <!-- Top Nav start Here -->
    <div class="bg-dark" style="color:white; border-radius: none;">
      <offerNav/>
    </div>
    <!-- Top Nav end Here -->

    <!-- Second Nav Start here -->
    <div>
      <menuNav/>
    </div>
    <!-- Second Nav end here -->

    <!-- Main Navbar start here-->
    <div class="position-relative sticky-top">
      <div>
        <b-navbar class="pb-2 pt-0 d-flex justify-content-between" type="dark" variant="none">
            <b-navbar-brand href="#" class="text-dark">
              <span sm="text-primary">
                <b-button v-b-toggle.sidebar-variant class="d-lg-none" variant="none">
                  <b-icon icon="menu-button-wide" size="lg" font-scale="2" animation="cylon-vertical"></b-icon>
                </b-button>
                <span class="h3">PORTO</span>
              </span>
            </b-navbar-brand>

          <!-- <b-navbar-toggle target="nav-collapse"></b-navbar-toggle> -->


            <!-- left side -->
            <b-navbar-nav class="d-none d-lg-block w-50">
              <b-form class="w-100 mr-sm-3 ml-5">
                <b-form-group class="mb-0">
                  <b-input-group class="input-group-alternative input-group-merge">
                    <b-form-input variant="primary" class="width-full" placeholder="Search..." type="text" style="height:40px;color:#808080; opacity:.75;border-radius: 25px 0px 0px 25px;"></b-form-input>
                    <div>
                      <b-dropdown text="All Categories" variant="none" class="border">
                        <b-dropdown-item>First Action</b-dropdown-item>
                        <b-dropdown-item>Second Action</b-dropdown-item>
                        <b-dropdown-item>Third Action</b-dropdown-item>
                        <b-dropdown-item>First Action</b-dropdown-item>
                        <b-dropdown-item>Second Action</b-dropdown-item>
                        <b-dropdown-item>Third Action</b-dropdown-item>
                      </b-dropdown>
                    </div>

                    <div class="input-group-append" style="">
                      <span class="input-group-text" style="background-color:white; opacity:.75;border-radius: 0px 25px 25px 0px;">
                        <b-icon icon="search"></b-icon>
                      </span>
                    </div>
                  </b-input-group>
                </b-form-group>
              </b-form>
            </b-navbar-nav>


            <!-- Toogle Search bar -->
            <div v-if="toggleSearch" class="position-absolute bottom-search">
              <b-navbar-nav class="w-50">
                <b-form class="w-100 mr-sm-3 ml-5">
                  <b-form-group class="mb-0">
                    <b-input-group class="input-group-alternative input-group-merge" style="border-radius: 50px; border: solid 3px;">
                      <b-form-input variant="primary" class="width-full border-0" placeholder="Search..." type="text" style="height:40px;color:#808080; opacity:.75;border-radius: 25px 0px 0px 25px;"></b-form-input>
                      <div hidden>
                        <b-dropdown text="All Categories" variant="none" class="border">
                          <b-dropdown-item>First Action</b-dropdown-item>
                          <b-dropdown-item>Second Action</b-dropdown-item>
                          <b-dropdown-item>Third Action</b-dropdown-item>
                          <b-dropdown-item>First Action</b-dropdown-item>
                          <b-dropdown-item>Second Action</b-dropdown-item>
                          <b-dropdown-item>Third Action</b-dropdown-item>
                        </b-dropdown>
                      </div>

                      <div class="input-group-append" style="">
                        <span class="input-group-text border-0" style="background-color:white; opacity:.75;border-radius: 0px 25px 25px 0px;">
                          <b-icon icon="search"></b-icon>
                        </span>
                      </div>
                    </b-input-group>
                  </b-form-group>
                </b-form>
              </b-navbar-nav>
            </div>




        <b-navbar>
            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto d-block d-lg-none">
                <b-icon icon="search" class="h2 pt-2 mr-2" @click="toggleSearchIcon"></b-icon>
            </b-navbar-nav>

            <b-navbar-nav class="mr-2 d-none d-lg-block">
                <!-- <svg xmlns="http://www.w3.org/2000/svg" style="width:35px; font-weight: normal;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
                </svg> -->
                <div class="d-flex">
                  <div style="margin-top: 25px; margin-right: 5px;">
                    <b-icon icon="telephone" font-scale="2"></b-icon>
                  </div>
                  <div class="card-title">
                    <p class="pt-4" style="font-size:10px;">CALL US NOW <br><span style="font-size:13px; font-weight:bold;">+2873627537266</span></p>
                  </div>
                </div>
            </b-navbar-nav>


            <b-navbar-nav class="ml-auto" style="gap:20px">
              <b-navbar-nav>
                <svg xmlns="http://www.w3.org/2000/svg" style="width:30px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
                </svg>
              </b-navbar-nav>

              <b-navbar-nav>
                <svg xmlns="http://www.w3.org/2000/svg" style="width:30px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z" />
                </svg>
              </b-navbar-nav>

              <b-avatar v-b-toggle.sidebar-right badge="0" badge-variant="danger" badge-top badge-offset="-0.3em" variant="none" class="align-center">
                <svg xmlns="http://www.w3.org/2000/svg" style="width:30px;" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
                </svg>
              </b-avatar>

            </b-navbar-nav>
        </b-navbar>
        </b-navbar>
      </div>

      <!-- Shopping Card Modal Start Here -->
      <div>
        <b-sidebar id="sidebar-right" title="Shopping Cart" right backdrop backdrop-variant="dark" shadow>
          <div class="px-3 py-2">

          </div>
        </b-sidebar>
      </div>
      <!-- Shopping Card Modal Start Here -->

    </div>
    <!-- Main Navbar end here-->

    <!-- Mobile Sidebar Menu Start here-->
    <div>
      <b-sidebar id="sidebar-variant" title="Menu" bg-variant="dark" text-variant="light" backdrop backdrop-variant="dark" shadow>
        <mobileSideMenu/>
      </b-sidebar>
    </div>
    <!-- Mobile Sidebar Menu end here-->

  </div>
</template>

<script>
import offerNav from './nav/offerNav.vue';
import menuNav from './nav/menuNav.vue';
export default {
  name: 'NuxtTutorial',
  components:{offerNav,menuNav},
  data(){
    return{
      toggleSearch:false
    }
  },
  methods:{
    toggleSearchIcon(){
      this.toggleSearch = !this.toggleSearch;
    }
  }
}
</script>

<style scoped>
.bottom-search{
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  top: 50px;
}
</style>
