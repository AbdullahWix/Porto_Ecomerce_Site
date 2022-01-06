<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="primary">

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-container>
          <!-- left side -->
          <b-navbar-nav>

            <b-nav-item-dropdown class="pl-3" text="ENG">
              <b-dropdown-item href="#">ENG</b-dropdown-item>
              <b-dropdown-item href="#">FRA</b-dropdown-item>
            </b-nav-item-dropdown>

            <b-nav-item-dropdown class="pl-3" text="USD">
              <b-dropdown-item href="#">EUR</b-dropdown-item>
              <b-dropdown-item href="#">USD</b-dropdown-item>
            </b-nav-item-dropdown>

          </b-navbar-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto" style="font-size:13px; letter-spacing:1px; gap:15px; font-weight:600">
            <b-link href="#" class="text-white">WELCOME TO PORTO!</b-link>
            <b-link href="#" class="text-white">MY ACCOUNT</b-link>
            <b-link href="#" class="text-white">CONTACT US</b-link>
            <b-link href="#" class="text-white">MY WISHLIST</b-link>
            <b-link href="#" class="text-white">SITE MAP</b-link>
            <b-link href="#" class="text-white">CART</b-link>
            <b-link href="#" class="text-white">LOG IN</b-link>
          </b-navbar-nav>
          <!-- icon -->
          <b-navbar-nav class="ml-5">
            <svg xmlns="http://www.w3.org/2000/svg" style="color:white; width:25px; margin-left:3px" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M12.395 2.553a1 1 0 00-1.45-.385c-.345.23-.614.558-.822.88-.214.33-.403.713-.57 1.116-.334.804-.614 1.768-.84 2.734a31.365 31.365 0 00-.613 3.58 2.64 2.64 0 01-.945-1.067c-.328-.68-.398-1.534-.398-2.654A1 1 0 005.05 6.05 6.981 6.981 0 003 11a7 7 0 1011.95-4.95c-.592-.591-.98-.985-1.348-1.467-.363-.476-.724-1.063-1.207-2.03zM12.12 15.12A3 3 0 017 13s.879.5 2.5.5c0-1 .5-4 1.25-4.5.5 1 .786 1.293 1.371 1.879A2.99 2.99 0 0113 13a2.99 2.99 0 01-.879 2.121z" clip-rule="evenodd" />
            </svg>
            <svg xmlns="http://www.w3.org/2000/svg" style="color:white; width:25px; margin-left:3px;" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M12.395 2.553a1 1 0 00-1.45-.385c-.345.23-.614.558-.822.88-.214.33-.403.713-.57 1.116-.334.804-.614 1.768-.84 2.734a31.365 31.365 0 00-.613 3.58 2.64 2.64 0 01-.945-1.067c-.328-.68-.398-1.534-.398-2.654A1 1 0 005.05 6.05 6.981 6.981 0 003 11a7 7 0 1011.95-4.95c-.592-.591-.98-.985-1.348-1.467-.363-.476-.724-1.063-1.207-2.03zM12.12 15.12A3 3 0 017 13s.879.5 2.5.5c0-1 .5-4 1.25-4.5.5 1 .786 1.293 1.371 1.879A2.99 2.99 0 0113 13a2.99 2.99 0 01-.879 2.121z" clip-rule="evenodd" />
            </svg>
            <svg xmlns="http://www.w3.org/2000/svg" style="color:white; width:25px; margin-left:3px;" viewBox="0 0 20 20" fill="currentColor">
              <path fill-rule="evenodd" d="M12.395 2.553a1 1 0 00-1.45-.385c-.345.23-.614.558-.822.88-.214.33-.403.713-.57 1.116-.334.804-.614 1.768-.84 2.734a31.365 31.365 0 00-.613 3.58 2.64 2.64 0 01-.945-1.067c-.328-.68-.398-1.534-.398-2.654A1 1 0 005.05 6.05 6.981 6.981 0 003 11a7 7 0 1011.95-4.95c-.592-.591-.98-.985-1.348-1.467-.363-.476-.724-1.063-1.207-2.03zM12.12 15.12A3 3 0 017 13s.879.5 2.5.5c0-1 .5-4 1.25-4.5.5 1 .786 1.293 1.371 1.879A2.99 2.99 0 0113 13a2.99 2.99 0 01-.879 2.121z" clip-rule="evenodd" />
            </svg>
          </b-navbar-nav>
        </b-container>

      </b-collapse>
    </b-navbar>
  </div>
</template>
