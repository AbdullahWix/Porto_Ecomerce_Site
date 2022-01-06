<template>
  <div>
    <!-- Hearder Nav -->
    <HeaderNav/>

    <!-- Breadcrumb start Here -->
    <b-container>
      <div class="my-2 d">
        <svg xmlns="http://www.w3.org/2000/svg" style="width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
        </svg>
        <svg xmlns="http://www.w3.org/2000/svg" style="width:14px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
        </svg>
        <span class="h6" style="font-size:15px;">SHOP</span>
      </div>
    </b-container>
    <!-- Breadcrumb end Here -->

    <!-- Sidebar start here -->
    <b-container class="bv-example-row">
      <b-row>
        <!-- Left side -->
        <b-col class="border">
          <categoriesSidebar/>
        </b-col>
        <!-- Right Side -->
        <b-col cols='9' class="">
          <!-- Product Top section start here -->
          <div>
            <b-list-group style="font-size:16px; font-weight:bold;">

              <b-list-group-item class="pl-1 pr-1 d-flex justify-content-between align-items-center" style="border:none">
                <div>
                  Sort By:
                  <b-dropdown size="sm" text="Default Sorting" variant="outline-dark" class="m-2">
                      <b-dropdown-item href="#">Action</b-dropdown-item>
                      <b-dropdown-item href="#">Another action</b-dropdown-item>
                      <b-dropdown-item href="#">Something else here</b-dropdown-item>
                    </b-dropdown>
                </div>

                <div class="d-flex align-items-center">
                  <h6>Show:</h6>
                  <b-dropdown size="sm" text="5" variant="outline-dark" class="m-2">
                    <b-dropdown-item href="#">1</b-dropdown-item>
                    <b-dropdown-item href="#">2</b-dropdown-item>
                    <b-dropdown-item href="#">3</b-dropdown-item>
                    <b-dropdown-item href="#">4</b-dropdown-item>
                    <b-dropdown-item href="#">5</b-dropdown-item>
                  </b-dropdown>
                  <div @click="showGrid">
                    <svg xmlns="http://www.w3.org/2000/svg" style="width:28px;" :style="{color:gridView ? '#007bff' : ''}"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z" />
                    </svg>
                  </div>
                  <div @click="showList">
                    <svg xmlns="http://www.w3.org/2000/svg" style="width:28px;" :style="{color:listView ? '#007bff' : ''}" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 10h16M4 14h16M4 18h16" />
                    </svg>
                  </div>
                </div>


              </b-list-group-item>
            </b-list-group>
          </div>
          <!-- Product Top section end here -->

          <!-- product cart section start here-->
          <div class="ml-4">

            <!-- grid view start here -->
            <b-row v-if="gridView" align-v="center">
              <b-col v-for="index in 6" :key="index" cols="4">
                <NuxtLink to="/product_details">
                  <productGridView/>
                </NuxtLink>
              </b-col>
            </b-row>
            <!-- grid view end here -->

            <!-- List view start here -->
            <b-row v-if="listView">
                <div v-for="index in 2" :key="index">
                  <productListView/>
                </div>
            </b-row>
            <!-- List view end here -->

          </div>
          <!-- product cart section end here-->

          <!--Product Card Pagination start here -->
          <div>
            <b-list-group-item class="pl-1 pr-1 d-flex justify-content-between align-items-center" style="border:none">
              <div class="d-flex align-items-center">
                <h6>Show:</h6>
                <b-dropdown size="sm" text="5" variant="outline-dark" class="m-2">
                  <b-dropdown-item href="#">1</b-dropdown-item>
                  <b-dropdown-item href="#">2</b-dropdown-item>
                  <b-dropdown-item href="#">3</b-dropdown-item>
                  <b-dropdown-item href="#">4</b-dropdown-item>
                  <b-dropdown-item href="#">5</b-dropdown-item>
                </b-dropdown>
              </div>

              <div class="">
                <div>
                  <b-pagination v-model="currentPage" :total-rows="rows"></b-pagination>
                </div>
              </div>

            </b-list-group-item>
          </div>
          <!--Product Card Pagination end here -->


        </b-col>

      </b-row>
    </b-container>
    <!-- Sidebar end here -->
  </div>
</template>
<script>
export default {
  name: 'SidebarMenu',
  data(){
    return{
      gridView:false,
      listView:true,
      rows: 100,
      currentPage: 3
    }
  },
  methods:{
    showGrid(){
      this.gridView =true;
      this.listView=false;
    },
    showList(){
      this.listView=true;
      this.gridView =false;
    },
  }

}
</script>

<style scope>

</style>
