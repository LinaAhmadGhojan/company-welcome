<template>
  <section class="agency_section layout_padding2-top">
    <div class="agency_container ">
      <div class="box ">
        <div class="detail-box">
          <div class="heading_container">
            <h2>
              About <span>Design</span> Agency
            </h2>
          </div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum
          </p>
          <a href="">
            Read More
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- end agency section -->



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
    <section class=" footer_section">
      <div class="container">
        <p>
          &copy; <span id="displayYear"></span> All Rights Reserved By
          <a href="https://html.design/">Free Html Templates</a>
        </p>
      </div>
    </section>
    <!-- footer section -->

  </section>

  <!-- end info section -->

</template>

<script>

export default {
  data: function()
 { 
  return {
    pagename:"about",
    pagedescription:"This is an about page"
  } ;
},
name:"about"
    
  }


</script>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }

  .class-about{
    text-align: center;
  }
}
</style>
