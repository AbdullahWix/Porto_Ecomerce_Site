<template>
  <div class="container mt-5 d-none d-lg-block">
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
              <b-col v-for="r in 4" :key="r">
                <mainCard/>
              </b-col>
            </b-row>
          </div>
        </b-tab>

        <b-tab title="NEW ARRIVALS">
          <div>
            <b-row>
              <b-col v-for="r in 4" :key="r">
                <mainCard/>
              </b-col>
            </b-row>
          </div>
        </b-tab>

        <b-tab title="TODAYS DEALS">
          <div>
            <b-row>
              <b-col v-for="r in 4" :key="r">
                <mainCard/>
              </b-col>
            </b-row>
          </div>
        </b-tab>

    </b-tabs>
  </div>
</template>
