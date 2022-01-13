<template>
  <div>
    <b-navbar type="dark" variant="primary">

      <!-- <b-navbar-toggle target="nav-collapse"></b-navbar-toggle> -->

        <b-container>
          <!-- left side -->
          <b-navbar-nav class="flex-row">
              <b-nav-item-dropdown class="pl-3" text="ENG" style="font-color:white">
                <b-dropdown-item href="#" class="text-white">ENG</b-dropdown-item>
                <b-dropdown-item href="#">FRA</b-dropdown-item>
              </b-nav-item-dropdown>

              <b-nav-item-dropdown class="pl-3" text="USD">
                <b-dropdown-item href="#">EUR</b-dropdown-item>
                <b-dropdown-item href="#">USD</b-dropdown-item>
              </b-nav-item-dropdown>

          </b-navbar-nav>

            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto pl-5 d-block d-lg-none" style="font-size:13px; letter-spacing:1px; gap:15px; font-weight:600">
              <b-link href="#" class="text-white">WELCOME TO PORTO!</b-link>
            </b-navbar-nav>

            <b-navbar-nav class="mr-auto d-block d-lg-none" style="font-size:13px; letter-spacing:1px; gap:15px; font-weight:600">
              <b-nav-item-dropdown class="pl-3" text="Link">
                <b-dropdown-item href="#">Link-1</b-dropdown-item>
                <b-dropdown-item href="#">Link-2</b-dropdown-item>
                <b-dropdown-item href="#">Link-3</b-dropdown-item>
                <b-dropdown-item href="#">Link-4</b-dropdown-item>
                <b-dropdown-item href="#">Link-5</b-dropdown-item>
                <b-dropdown-item href="#">Link-6</b-dropdown-item>
              </b-nav-item-dropdown>
            </b-navbar-nav>

            <b-navbar-nav class="d-none d-lg-block ml-auto" style="font-size:13px; letter-spacing:1px; gap:15px; font-weight:600">
              <b-link href="#" class="text-white mx-1">WELCOME TO PORTO!</b-link>
              <b-link href="#" class="text-white mx-1">MY ACCOUNT</b-link>
              <b-link href="#" class="text-white mx-1">CONTACT US</b-link>
              <b-link href="#" class="text-white mx-1">MY WISHLIST</b-link>
              <b-link href="#" class="text-white mx-1">SITE MAP</b-link>
              <b-link href="#" class="text-white mx-1">CART</b-link>
              <b-link href="#" class="text-white mx-1">LOG IN</b-link>
            </b-navbar-nav>
            <!-- icon -->
            <b-navbar-nav class="d-inline">
              <b-icon class="mx-1" icon="facebook" variant="white" aria-hidden="true"></b-icon>
              <b-icon class="mx-1" icon="twitter" variant="white" aria-hidden="true"></b-icon>
              <b-icon class="mx-1" icon="instagram" variant="white" aria-hidden="true"></b-icon>
            </b-navbar-nav>
          <!-- </b-collapse> -->
        </b-container>
    </b-navbar>
  </div>
</template>
