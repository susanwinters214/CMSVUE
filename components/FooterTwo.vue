<template>
  <footer
    class="footer-area bg-img-cover"
    :style="{ backgroundImage: `url('/images/photos/bg-footer.jpg')` }"
  >
    <div class="container" data-aos="fade-up" data-aos-duration="1000">
      <div class="row">
        <div class="col-md-9 col-lg-4 col-xl-4">
          <div class="widget-item mt-0">
            <div class="about-widget">
              <NuxtLink to="/" class="footer-logo">
                <img src="/images/logo/logo.png" alt="Logo" />
              </NuxtLink>
              <p>
                Lorem Ipsum is simply dummy text of the and typesetting
                industry. Lorem Ipsum has industry's standard dummy text ever
                printer took a galley.
              </p>
              <div class="widget-newsletter">
                <form>
                  <input
                    type="email"
                    class="form-control"
                    placeholder="Enter your email"
                  />
                  <button type="submit" class="btn btn-theme">
                    Subscribe Now <i class="icon icofont-long-arrow-right"></i>
                  </button>
                </form>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-8 col-lg-6 col-xl-6">
          <div class="widget-item menu-wrap-two-column">
            <h4 class="widget-title">All Services</h4>
            <img
              class="line-shape"
              src="/images/shape/line-s1.png"
              alt="shape"
            />
            <nav class="widget-menu-wrap">
              <div class="row">
                <div class="col-md-6">
                  <ul class="nav-menu nav">
                    <li>
                      <NuxtLink to="/service-details"
                        >Business Management</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/service-details">Web Development</NuxtLink>
                    </li>
                    <li>
                      <NuxtLink to="/service-details"
                        >Business Consultation</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/service-details"
                        >Digital Marketing</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/service-details">Brand Identity</NuxtLink>
                    </li>
                    <li>
                      <NuxtLink to="/service-details"
                        >Insurance & Banking</NuxtLink
                      >
                    </li>
                  </ul>
                </div>
                <div class="col-md-6">
                  <ul class="nav-menu nav">
                    <li>
                      <NuxtLink to="/service-details"
                        >Website Optimization</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/service-details"
                        >Social Media Marketing</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/service-details"
                        >Link Building Services</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/service-details"
                        >Pay Per Click Advertising</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/service-details"
                        >Search Engine Marketing</NuxtLink
                      >
                    </li>
                    <li>
                      <NuxtLink to="/service-details"
                        >Content Marketing</NuxtLink
                      >
                    </li>
                  </ul>
                </div>
              </div>
            </nav>
          </div>
        </div>
        <div class="col-md-4 col-lg-2 col-xl-2 lg-pr-0">
          <div class="widget-item menu-wrap-column">
            <h4 class="widget-title">Useful Links</h4>
            <img
              class="line-shape"
              src="/images/shape/line-s1.png"
              alt="Virtuf-HasTech"
            />
            <nav class="widget-menu-wrap">
              <ul class="nav-menu nav">
                <li><NuxtLink to="/">Group Profile</NuxtLink></li>
                <li><NuxtLink to="/">Vision & Values</NuxtLink></li>
                <li><NuxtLink to="/">Company History</NuxtLink></li>
                <li><NuxtLink to="/">Careers</NuxtLink></li>
                <li><NuxtLink to="/">Winning Awards</NuxtLink></li>
                <li><NuxtLink to="/">Sustainability</NuxtLink></li>
              </ul>
            </nav>
          </div>
        </div>
      </div>
    </div>
    <div class="footer-bottom">
      <div class="container">
        <div class="footer-bottom-content">
          <div class="row align-items-center">
            <div class="col-md-6 order-2 order-md-1">
              <div class="widget-copyright">
                <p>
                  © 2023 <span>VIRTUF</span> Made with
                  <i class="icofont-heart"></i> by <a href="#">HasThemes</a>
                </p>
              </div>
            </div>
            <div class="col-md-6 order-1 order-md-2">
              <div class="widget-social-icons">
                <a href="#"><i class="icofont-facebook"></i></a>
                <a href="#"><i class="icofont-skype"></i></a>
                <a href="#"><i class="icofont-instagram"></i></a>
                <a href="#"><i class="icofont-twitter"></i></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>
