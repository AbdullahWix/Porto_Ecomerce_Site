<template>
  <div class="container mt-5 d-none d-lg-block" style="min-width:540px">
    <div class="text-center">
      <p class="font-weight-bold text-dark">FEATURED PRODUCTS</p>
      <hr>
    </div>
    <!-- Featured Product Section -->
    <div class="container d-flex justify-content-between align-items-center">
      <div class="bg-secondary text-white py-3 px-4 mr-3">
        <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18" />
        </svg>
      </div>

      <div>
        <div class="scrolling-wrapper row flex-row flex-nowrap mt-4 pb-4 pt-2">
          <div class="col-4">
            <productGridCard/>
          </div>
          <div class="col-4">
            <productGridCard/>
          </div>
          <div class="col-4">
            <productGridCard/>
          </div>
          <div class="col-4">
            <productGridCard/>
          </div>
          <div class="col-4">
            <productGridCard/>
          </div>
          <div class="col-4">
            <productGridCard/>
          </div>
        </div>
      </div>



      <div class="bg-secondary text-light py-3 px-4 ml-3">
        <svg xmlns="http://www.w3.org/2000/svg" style="width:20px" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3" />
        </svg>
      </div>
    </div>

    <!-- <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div :id="carousel123" class="carousel carousel-showmanymoveone slide">
            <div class="carousel-inner">
              <div class="item active">
                <div class="col-xs-12 col-sm-6 col-md-3">
                  <a href="#">
                    <img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" class="img-responsive">  </a>
                </div>
              </div>
              <div class="item">
                <div class="col-xs-12 col-sm-6 col-md-3">
                  <a href="#"><img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" class="img-responsive">
                  </a>
                </div>
              </div>
              <div class="item">
                <div class="col-xs-12 col-sm-6 col-md-3"><a href="#"><img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" class="img-responsive"></a></div>
              </div>
              <div class="item">
                <div class="col-xs-12 col-sm-6 col-md-3"><a href="#"><img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" class="img-responsive"></a></div>
              </div>
              <div class="item">
                <div class="col-xs-12 col-sm-6 col-md-3"><a href="#"><img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" class="img-responsive"></a></div>
              </div>
              <div class="item">
                <div class="col-xs-12 col-sm-6 col-md-3"><a href="#"><img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" class="img-responsive"></a></div>
              </div>
              <div class="item">
                <div class="col-xs-12 col-sm-6 col-md-3"><a href="#"><img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" class="img-responsive"></a></div>
              </div>
              <div class="item">
                <div class="col-xs-12 col-sm-6 col-md-3"><a href="#"><img src="https://s3.eu-central-1.amazonaws.com/bootstrapbaymisc/blog/24_days_bootstrap/vans.png" class="img-responsive"></a></div>
              </div>
            </div>
            <a class="left carousel-control" href="#carousel123" data-slide="prev"><i class="glyphicon glyphicon-chevron-left"></i></a>
            <a class="right carousel-control" href="#carousel123" data-slide="next"><i class="glyphicon glyphicon-chevron-right"></i></a>
          </div>
        </div>
      </div>
    </div> -->


  </div>
</template>

<script>
export default {
  data(){
    return{
      carousel123:true
    }
  },
  methode:{
    function(){
      this.carousel123.carosel({interval: 2000});
    }

  }
}
</script>

<style scoped>
.scrolling-wrapper{
  scrollbar-width: none;
  -ms-overflow-style: none;
	overflow-x: auto;
}
.scrolling-wrapper::-webkit-scrollbar {
  display: none;
}
.carousel-showmanymoveone .carousel-control {
  width: 4%;
  background-image: none;
}
.carousel-showmanymoveone .carousel-control.left {
  margin-left: 15px;
}
.carousel-showmanymoveone .carousel-control.right {
  margin-right: 15px;
}
.carousel-showmanymoveone .cloneditem-1,
.carousel-showmanymoveone .cloneditem-2,
.carousel-showmanymoveone .cloneditem-3 {
  display: none;
}
@media all and (min-width: 768px) {
  .carousel-showmanymoveone .carousel-inner > .active.left,
  .carousel-showmanymoveone .carousel-inner > .prev {
    left: -50%;
  }
  .carousel-showmanymoveone .carousel-inner > .active.right,
  .carousel-showmanymoveone .carousel-inner > .next {
    left: 50%;
  }
  .carousel-showmanymoveone .carousel-inner > .left,
  .carousel-showmanymoveone .carousel-inner > .prev.right,
  .carousel-showmanymoveone .carousel-inner > .active {
    left: 0;
  }
  .carousel-showmanymoveone .carousel-inner .cloneditem-1 {
    display: block;
  }
}
@media all and (min-width: 768px) and (transform-3d), all and (min-width: 768px) and (-webkit-transform-3d) {
  .carousel-showmanymoveone .carousel-inner > .item.active.right,
  .carousel-showmanymoveone .carousel-inner > .item.next {
    -webkit-transform: translate3d(50%, 0, 0);
            transform: translate3d(50%, 0, 0);
    left: 0;
  }
  .carousel-showmanymoveone .carousel-inner > .item.active.left,
  .carousel-showmanymoveone .carousel-inner > .item.prev {
    -webkit-transform: translate3d(-50%, 0, 0);
            transform: translate3d(-50%, 0, 0);
    left: 0;
  }
  .carousel-showmanymoveone .carousel-inner > .item.left,
  .carousel-showmanymoveone .carousel-inner > .item.prev.right,
  .carousel-showmanymoveone .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
            transform: translate3d(0, 0, 0);
    left: 0;
  }
}
@media all and (min-width: 992px) {
  .carousel-showmanymoveone .carousel-inner > .active.left,
  .carousel-showmanymoveone .carousel-inner > .prev {
    left: -25%;
  }
  .carousel-showmanymoveone .carousel-inner > .active.right,
  .carousel-showmanymoveone .carousel-inner > .next {
    left: 25%;
  }
  .carousel-showmanymoveone .carousel-inner > .left,
  .carousel-showmanymoveone .carousel-inner > .prev.right,
  .carousel-showmanymoveone .carousel-inner > .active {
    left: 0;
  }
  .carousel-showmanymoveone .carousel-inner .cloneditem-2,
  .carousel-showmanymoveone .carousel-inner .cloneditem-3 {
    display: block;
  }
}
@media all and (min-width: 992px) and (transform-3d), all and (min-width: 992px) and (-webkit-transform-3d) {
  .carousel-showmanymoveone .carousel-inner > .item.active.right,
  .carousel-showmanymoveone .carousel-inner > .item.next {
    -webkit-transform: translate3d(25%, 0, 0);
            transform: translate3d(25%, 0, 0);
    left: 0;
  }
  .carousel-showmanymoveone .carousel-inner > .item.active.left,
  .carousel-showmanymoveone .carousel-inner > .item.prev {
    -webkit-transform: translate3d(-25%, 0, 0);
            transform: translate3d(-25%, 0, 0);
    left: 0;
  }
  .carousel-showmanymoveone .carousel-inner > .item.left,
  .carousel-showmanymoveone .carousel-inner > .item.prev.right,
  .carousel-showmanymoveone .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
            transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.container {
  margin-bottom: 50px;
}
body {
  font-family: 'Bitter', sans-serif;
  color: #E54A41;
  background-image: url('//static.rtpdesign.co.uk/blog/img/background.png');
  background-repeat: no-repeat;
  background-position: right top;
  background-size: 20%;
}
p {
  font-family: 'Open Sans', sans-serif;
  color: #333;
  margin-bottom: 2em;
}
h2 {
  margin: 2em 0 1em;
}
.logo {
  margin: 20px auto;
  height: 100px;
}
@media only screen and (min-width: 768px) {
  .logo {
    margin: 28px;
    float: left;
  }
}
.title {
  padding: 28px;
  display: table-cell;
  position: relative;
  vertical-align: middle;
  text-align: center;
}

</style>
