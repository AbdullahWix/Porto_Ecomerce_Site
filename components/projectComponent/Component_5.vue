<template>
  <div>
    <div class="text-center">
      <p class="h4 font-weight-bold text-dark">COMPONENT-5</p>
      <hr>
    </div>

    <div>
      <b-container class="bv-example-row">
        <b-row>
          <!-- left side -->
          <b-col cols="3">
            <div class="mb-4">
              <!-- shop by category -->
              <b-list-group-item class="d-flex align-items-center bg-dark text-light" variant="" style="cursor: pointer; user-select: none; gap:10px">
                  <svg xmlns="http://www.w3.org/2000/svg" style="width:28px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                  </svg>

                <span class="mr-auto font-weight-bold">SHOP BY CATEGORY</span>
              </b-list-group-item>

              <!-- Side menu list -->
              <b-list-group-item class="d-flex align-items-center" variant="" style="cursor: pointer; user-select: none;">
                <b-avatar class="mr-1" variant="none">
                  <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:25px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
                  </svg>
                </b-avatar>
                <span class="font-weight-bold" style="color:#808080;">Home</span>
              </b-list-group-item>

              <b-list-group-item class="d-flex align-items-center" variant="" style="cursor: pointer; user-select: none;">
                <b-avatar class="mr-1" variant="none">
                  <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:25px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                  </svg>
                </b-avatar>
                <span class="mr-auto font-weight-bold" style="color:#808080;">Categories</span>
                <b-badge variant="none">
                  <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                  </svg>

                  <!-- <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                  </svg> -->
                </b-badge>
              </b-list-group-item>

              <b-list-group-item class="d-flex align-items-center" variant="" style="cursor: pointer; user-select: none;">
                <b-avatar class="mr-1" variant="none">
                  <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:25px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v13m0-13V6a2 2 0 112 2h-2zm0 0V5.5A2.5 2.5 0 109.5 8H12zm-7 4h14M5 12a2 2 0 110-4h14a2 2 0 110 4M5 12v7a2 2 0 002 2h10a2 2 0 002-2v-7" />
                  </svg>
                </b-avatar>
                <span class="mr-auto font-weight-bold" style="color:#808080;">Products</span>
                <b-badge variant="none">
                  <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                  </svg>

                  <!-- <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                  </svg> -->
                </b-badge>
              </b-list-group-item>

              <b-list-group-item class="d-flex align-items-center" variant="" style="cursor: pointer; user-select: none;">
                <b-avatar class="mr-1" variant="none">
                  <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:25px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7v8a2 2 0 002 2h6M8 7V5a2 2 0 012-2h4.586a1 1 0 01.707.293l4.414 4.414a1 1 0 01.293.707V15a2 2 0 01-2 2h-2M8 7H6a2 2 0 00-2 2v10a2 2 0 002 2h8a2 2 0 002-2v-2" />
                  </svg>
                </b-avatar>
                <span class="mr-auto font-weight-bold" style="color:#808080;">Pages</span>
                <b-badge variant="none">
                  <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" />
                  </svg>

                  <!-- <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:18px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7" />
                  </svg> -->
                </b-badge>
              </b-list-group-item>

              <b-list-group-item class="d-flex align-items-center" variant="" style="cursor: pointer; user-select: none;">
                <b-avatar class="mr-1" variant="none">
                  <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:25px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
                  </svg>
                </b-avatar>
                <span class="font-weight-bold" style="color:#808080;">Blog</span>
              </b-list-group-item>

              <b-list-group-item class="d-flex align-items-center" variant="" style="cursor: pointer; user-select: none;">
                <b-avatar class="mr-1" variant="none">
                  <svg xmlns="http://www.w3.org/2000/svg" style="color:#808080; width:25px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z" />
                  </svg>
                </b-avatar>
                <span class="font-weight-bold" style="color:#808080;">About Us</span>
              </b-list-group-item>

              <b-list-group-item class="d-flex align-items-center text-dark" variant="secondary" style="cursor: pointer; user-select: none; gap:10px">
                <span class="text-center font-weight-bold">HUGE SALE - 70% OFF</span>
              </b-list-group-item>
            </div>
          </b-col>

          <!-- Right Side -->
          <b-col cols="9">
            <div>
              <div class="d-flex justify-content-end align-items-center" style="font-size:14px; letter-spacing:1px; gap:20px; font-weight:800;padding-top:8px">
                  <b-link href="#" class="text-dark">WOMAN SHOES</b-link>
                  <b-link href="#" class="text-dark">50% OFF FASHION</b-link>
                  <b-link href="#" class="text-dark">BUY PORTO!</b-link>
              </div>
            </div>
            <div class="mt-4">
              <!-- <img style="width:825px; object-fit:contain" src="../../store/banner.png" alt="banner"> -->
              <b-img src="../../store/banner.png" fluid alt="Responsive image" style="height:440px;"></b-img>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>
