<template>
    <div>
      <div>
        <b-list-group style="font-size:20px; font-weight:bold;">

          <b-list-group style="font-size:16px; font-weight:bold;">

          <b-list-group-item class="pl-1 pr-1 d-flex justify-content-between align-items-center" style="border:none">
            CATEGORIES
            <b-badge variant="none">
              <b-icon icon="dash" font-scale="1.50"></b-icon>
            </b-badge>
          </b-list-group-item>
        </b-list-group>

        </b-list-group>

        <b-list-group style="font-size:15px; color:gray; font-weight:600;">

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Cloth(5)
            <b-badge variant="none">
              <b-icon icon="chevron-down" font-scale="1.50"></b-icon>
            </b-badge>
          </b-list-group-item>

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Com(7)
            <b-badge variant="none">
              <b-icon icon="chevron-down" font-scale="1.50"></b-icon>
            </b-badge>
          </b-list-group-item>

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Dress(5)
            <b-badge variant="none">
              <b-icon icon="chevron-down" font-scale="1.50"></b-icon>
            </b-badge>
          </b-list-group-item>

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Fashion(4)
            <b-badge variant="none">
              <b-icon icon="chevron-down" font-scale="1.50"></b-icon>
            </b-badge>
          </b-list-group-item>

          <b-list-group-item class="p-1 d-flex justify-content-between align-items-center" style="border:none">
            Trousers(5)
            <b-badge variant="none">
              <b-icon icon="chevron-down" font-scale="1.50"></b-icon>
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
              <b-icon icon="dash" font-scale="1.50"></b-icon>
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

      <!-- Color -->
      <div>
        <b-list-group style="font-size:16px; font-weight:bold;">

          <b-list-group-item class="pl-1 pr-1 d-flex justify-content-between align-items-center" style="border:none">
            COLOR
            <b-badge variant="none">
              <b-icon icon="dash" font-scale="1.50"></b-icon>
            </b-badge>
          </b-list-group-item>
        </b-list-group>

        <div class="d-flex justify-content-between mb-3">
          <div style="width:40px;height:40px;border:1px; background-color:red;"></div>
          <div style="width:40px;height:40px;border:1px; background-color:gray;"></div>
          <div style="width:40px;height:40px;border:1px; background-color:green;"></div>
          <div style="width:40px;height:40px;border:1px; background-color:blue;"></div>
          <div style="width:40px;height:40px;border:1px; background-color:yellow;"></div>
        </div>
      </div>

      <!-- Size -->
      <div>
        <b-list-group style="font-size:16px; font-weight:bold;">

          <b-list-group-item class="pl-1 pr-1 d-flex justify-content-between align-items-center" style="border:none">
            SIZES
            <b-badge variant="none">
              <b-icon icon="dash" font-scale="1.50"></b-icon>
            </b-badge>
          </b-list-group-item>
        </b-list-group>

        <div class="d-flex justify-content-start mb-3" style="gap:7px;">
          <div style="width:35px;height:31px;border:1px; border:solid 1px;">
            <p class="text-center font-weight-bold">XL</p>
          </div>
          <div style="width:35px;height:31px;border:1px; border:solid 1px;">
            <p class="text-center font-weight-bold">L</p>
          </div>
          <div style="width:35px;height:31px;border:1px; border:solid 1px;">
            <p class="text-center font-weight-bold">M</p>
          </div>
          <div style="width:35px;height:31px;border:1px; border:solid 1px;">
            <p class="text-center font-weight-bold">S</p>
          </div>
        </div>



      </div>
    </div>
</template>
