<template>
  <div class="mx-3" style="min-width:540px">
    <!-- Hearder Nav -->
    <HeaderNav class="d-none d-lg-block"/>

    <!-- Breadcrumb start Here -->
    <b-container>
      <div class="my-2 d">
        <b-icon icon="house-fill" font-scale="1.25"></b-icon>
        <b-icon icon="chevron-right" font-scale="1"></b-icon>
        <span class="h6" style="font-size:15px;">SHOP</span>
      </div>
    </b-container>
    <!-- Breadcrumb end Here -->

    <!-- Sidebar start here -->
    <b-container>
      <b-row>
        <!-- Left side -->
        <b-col sm="12" lg="3" class="mt-3 border d-none d-lg-block">
          <categoriesSidebar/>
        </b-col>
        <!-- Right Side -->
        <b-col class="" sm="12" lg="9">
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
                  <h6 class="mx-1">Show:</h6>
                  <b-form-select
                    id="inline-form-custom-select-pref"
                    class="mr-sm-2 mb-sm-0"
                    :options="[{ text: '1', value: null }, '1', '2', '3' ,'4' ,'5' ,'6', '7', '8','9','10']"
                    :value="10"
                  ></b-form-select>
                  <div class="mx-1" @click="showGrid">
                    <b-icon icon="grid" font-scale="1.5" :style="{color:gridView ? '#007bff' : ''}"></b-icon>
                  </div>
                  <div class="mx-1" @click="showList">
                    <b-icon icon="list-ul" font-scale="1.75" :style="{color:listView ? '#007bff' : ''}"></b-icon>
                  </div>
                </div>


              </b-list-group-item>
            </b-list-group>
          </div>
          <!-- Product Top section end here -->

          <!-- product cart section start here-->
          <div class="ml-3">

            <!-- grid view start here -->
            <b-row v-if="gridView">
              <b-col v-for="index in 6" :key="index" class="p-1" cols="6" md="4">
                <NuxtLink style="text-decoration: none;" to="/product_details">
                  <productGridCard/>
                </NuxtLink>
              </b-col>
            </b-row>
            <!-- grid view end here -->

            <!-- List view start here -->
            <b-row v-if="listView">
                <b-row v-for="index in 2" :key="index" cols="12">
                  <productListCard/>
                </b-row>
            </b-row>
            <!-- List view end here -->

          </div>
          <!-- product cart section end here-->

          <!--Product Card Pagination start here -->
          <div>
            <b-list-group-item class="pl-1 pr-1 d-flex justify-content-between align-items-center" style="border:none">
              <div class="d-flex align-items-center">
                <h6 class="mx-1">Show:</h6>
                <b-form-select
                    id="inline-form-custom-select-pref"
                    class="mr-sm-2 mb-sm-0"
                    :options="[{ text: '1', value: null }, '1', '2', '3' ,'4' ,'5' ,'6', '7', '8','9','10']"
                    :value="10"
                  ></b-form-select>
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
      gridView:true,
      listView:false,
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
