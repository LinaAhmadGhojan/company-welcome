<template>

  <section class="service_section layout_padding-bottom layout_padding2-top">
    <div class="container">
      <div class="heading_container">
        <h2>
          Ser<span>vi</span>ces
        </h2>
        <p>
          adipiscingelit,sed do eiusmod tempor incididunt ut labore et dolore magn
        </p>
      </div>
      <div class="row">
        <div class="col-lg-6 ">
          <div class="img-container tab-content">
            <div class="img-box tab-pane fade show active" id="img1" role="tabpanel">
              <img src="../assets/image/service-img.jpg" alt="" />
            </div>
            <div class="img-box tab-pane fade  " id="img2" role="tabpanel">
              <img src="../assets/image/service-img.jpg" alt="" />
            </div>
            <div class="img-box tab-pane fade  " id="img3" role="tabpanel">
              <img src="../assets/image/service-img.jpg" alt="" />
            </div>
            <div class="img-box tab-pane fade  " id="img4" role="tabpanel">
              <img src="../assets/image/service-img.jpg" alt="" />
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="detail-container nav nav-tabs" id="myTab" role="tablist">
            <div class="detail-box active" id="img1-tab" data-toggle="tab" href="#img1" role="tab" aria-selected="true">
              <h4>
                Website <br />
                design
              </h4>
            </div>
            <div class="detail-box" id="img2-tab" data-toggle="tab" href="#img2" role="tab" aria-selected="false">
              <h4>
                Logo <br />
                design
              </h4>
            </div>
            <div class="detail-box" id="img2-tab" data-toggle="tab" href="#img3" role="tab" aria-selected="false">
              <h4>
                brochure <br />
                design
              </h4>
            </div>
            <div class="detail-box" id="img2-tab" data-toggle="tab" href="#img4" role="tab" aria-selected="false">
              <h4>
                visiting card <br />
                design
              </h4>
            </div>
          </div>
        </div>
      </div>
      <div class="btn-box">
        <a href="">
          Read More
        </a>
      </div>
    </div>
  </section>

  <!-- end service section -->


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
</template>

<script>
import BlogPost from '../components/blog/BlogPost.vue';
import BlogSlid from '../components/blog/BlogSlid.vue';
export default {
  data: function()
 { 
  return {
    pagename:"blog",
    pagedescription:"This is an blog page"
  } ;
},
name:"blog",
components:{
  BlogPost,BlogSlid
}
    
  }


</script>
  <style>
  @media (min-width: 1024px) {
    .help {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }

    .class-blog{
      text-align: center;
    }

    .posts-area{
      text-align: center;
      background-color: #fef8f0;
      padding: 20px;

    }

    .posts-sild{
      text-align: left;

    }
    
  }
  </style>
  