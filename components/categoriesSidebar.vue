<template>
    <div>
      <div>
        <b-list-group style="font-size:20px; font-weight:bold;">

          <b-list-group-item class="pl-1 pr-1 d-flex justify-content-between align-items-center" style="border:none">
            CATEGORIES
            <b-badge variant="none">
              <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18 12H6" />
              </svg>
            </b-badge>
          </b-list-group-item>

        </b-list-group>

        <b-list-group style="font-size:15px; color:gray; font-weight:600;">

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Cloth(5)
            <b-badge variant="none">
              <svg xmlns="http://www.w3.org/2000/svg" style="width:15px"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
              </svg>
            </b-badge>
          </b-list-group-item>

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Com(7)
            <b-badge variant="none">
              <svg xmlns="http://www.w3.org/2000/svg" style="width:15px"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
              </svg>
            </b-badge>
          </b-list-group-item>

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Dress(5)
            <b-badge variant="none">
              <svg xmlns="http://www.w3.org/2000/svg" style="width:15px"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
              </svg>
            </b-badge>
          </b-list-group-item>

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Fashion(4)
            <b-badge variant="none">
              <svg xmlns="http://www.w3.org/2000/svg" style="width:15px"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
              </svg>
            </b-badge>
          </b-list-group-item>

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Trousers(5)
            <b-badge variant="none">
              <svg xmlns="http://www.w3.org/2000/svg" style="width:15px"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
              </svg>
            </b-badge>
          </b-list-group-item>

        </b-list-group>
      </div>

      <hr>

      <div>
        <b-button squared variant="primary">Reset All Filters</b-button>
      </div>

      <hr>

      <div>
        <b-list-group style="font-size:16px; font-weight:bold;">

          <b-list-group-item class="pl-1 pr-1 d-flex justify-content-between align-items-center" style="border:none">
            PRICE
            <b-badge variant="none">
              <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18 12H6" />
              </svg>
            </b-badge>
          </b-list-group-item>
        </b-list-group>

        <form>
          <div>
            <input type="range" name="price-min" value="100" min="0" max="100" style="width:100%">
          </div>
        </form>

        <b-list-group style="font-size:12px; color:gray; font-weight:600;">
          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Price: $0.00 - $1000.00
            <b-badge variant="none">
              <b-button size="sm" squared variant="primary">FILTER</b-button>
            </b-badge>
          </b-list-group-item>
        </b-list-group>
      </div>

      <hr>

      <div>
        <b-list-group style="font-size:16px; font-weight:bold;">

          <b-list-group-item class="pl-1 pr-1 d-flex justify-content-between align-items-center" style="border:none">
            COLOR
            <b-badge variant="none">
              <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M18 12H6" />
              </svg>
            </b-badge>
          </b-list-group-item>
        </b-list-group>

        <div class="d-flex justify-content-between mb-3">
          <div style="width:50px;height:50px;border:1px; background-color:red;"></div>
          <div style="width:50px;height:50px;border:1px; background-color:gray;"></div>
          <div style="width:50px;height:50px;border:1px; background-color:green;"></div>
          <div style="width:50px;height:50px;border:1px; background-color:blue;"></div>
        </div>

      </div>
    </div>
</template>
