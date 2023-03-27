<template>
  
  <section class="portfolio_section layout_padding2-top">
    <div class="heading_container">
      <h2>
        Por<span>tf</span>olio
      </h2>
      <p>
        adipiscingelit,sed do eiusmod tempor incididunt ut labore et dolore magn
      </p>
    </div>
    <div class="portfolio_container layout_padding">
      <div class="box-1">
        <div class="img-box b-1">
          <img src="../assets/image/p1.jpg" alt="">
          <div class="btn-box">
            <a href="" class="btn-1">

            </a>
            <a href="" class="btn-2">

            </a>
          </div>
        </div>
        <div class="img-box b-2">
          <img src="../assets/image/p2.jpg" alt="">
          <div class="btn-box">
            <a href="" class="btn-1">

            </a>
            <a href="" class="btn-2">

            </a>
          </div>
        </div>
      </div>
      <div class="box-2">
        <div class="img-box b-3">
          <img src="../assets/image/p3.jpg" alt="">
          <div class="btn-box">
            <a href="" class="btn-1">

            </a>
            <a href="" class="btn-2">

            </a>
          </div>
        </div>
        <div class="img-box b-4">
          <img src="../assets/image/p4.jpg" alt="">
          <div class="btn-box">
            <a href="" class="btn-1">

            </a>
            <a href="" class="btn-2">

            </a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- end portfolio section -->


  <!-- info section -->

  <section class="info_section  layout_padding2-top">
    <div class="social_container">
      <div class="social_box">
        <a href="">
          <img src="../assets/image/fb.png" alt="">
        </a>
        <a href="">
          <img src="../assets/image/twitter.png" alt="">
        </a>
        <a href="">
          <img src="../assets/image/linkedin.png" alt="">
        </a>
        <a href="">
          <img src="../assets/image/youtube.png" alt="">
        </a>
      </div>
    </div>
    <div class="info_container ">
      <div class="container">
        <div class="row">
          <div class="col-md-6 col-lg-3">
            <h6>
              ABOUT US
            </h6>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed doLorem ipsum dolor sit amet, consectetur adipiscing elit, sed doLorem ipsum dolor sit amet,
            </p>
          </div>
          <div class="col-md-6 col-lg-3">
            <h6>
              Instagram
            </h6>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipi
              scing elit, sed doLorem ipsum dolor sit
            </p>
          </div>
          <div class="col-md-6 col-lg-3">
            <h6>
              NEED HELP
            </h6>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed doLorem ipsum dolor sit amet, consectetur adipiscing elit, sed doLorem ipsum dolor sit amet,
            </p>
          </div>
          <div class="col-md-6 col-lg-3">
            <h6>
              CONTACT US
            </h6>
            <div class="info_link-box">
              <a href="">
                <img src="../assets/image/location.png" alt="">
                <span> Gb road 123 london Uk </span>
              </a>
              <a href="">
                <img src="../assets/image/call.png" alt="">
                <span>+01 12345678901</span>
              </a>
              <a href="">
                <img src="../assets/image/mail.png" alt="">
                <span> demo@gmail.com</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- footer section -->
    <section class="footer_section">
      <div class="container">
        <p>
          &copy; <span id="displayYear"></span> All Rights Reserved By
          <a href="https://html.design/">Free Html Templates</a>
        </p>
      </div>
    </section>
    <!-- footer section -->

  </section>
</template>

<script>

export default {
  data: function()
 { 
  return {
    pagename:"Help",
    pagedescription:"This is an help page"
  } ;
},
name:"help"
    
  }


</script>
  <style>
  @media (min-width: 1024px) {
    .help {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }

    .class-help{
      text-align: center;
    }
  }
  </style>
  