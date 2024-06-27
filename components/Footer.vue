<template>
    <footer class="footer-area bg-img-cover" :style="{ backgroundImage: `url('/images/photos/bg-footer.jpg')` }">
       
        <div class="container" data-aos="fade-up" data-aos-duration="1000">
            <div class="row">
                <div class="col-md-9 col-lg-4 col-xl-4">
                    <div class="widget-item mt-0">
                        <div class="about-widget">
                            <nuxt-link to="/" class="footer-logo">
                                <img src="/images/logo/logo.png" alt="Logo">
                            </nuxt-link>
                            <p></p>
                            <div class="widget-newsletter">
<!--
                                <form>
                                    <input type="email" class="form-control" placeholder="Enter your email">
                                    <button type="submit" class="btn btn-theme">
                                        Subscribe Now <i class="icon icofont-long-arrow-right"></i>
                                    </button>
                                </form>
-->
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-8 col-lg-6 col-xl-6">
                    <div class="widget-item menu-wrap-two-column">
                        <h4 class="widget-title">Services:</h4>
                      
                        <nav class="widget-menu-wrap">
                            <div class="row">
                                <div class="col-md-6">
                                    <ul class="nav-menu nav">
                                        <li><nuxt-link to="/web-design-services">Web Design Services</nuxt-link></li>
                                        <li><nuxt-link to="/seo-services">Search Engine Optimization</nuxt-link></li>
                                    </ul>
                                </div>
                                <div class="col-md-6">
                                  
                                </div>
                            </div>
                        </nav>
                    </div>
                </div>
                <div class="col-md-4 col-lg-2 col-xl-2 lg-pr-0">
                    <div class="widget-item menu-wrap-column">
                       <!--
                        <h4 class="widget-title">Useful Links</h4>
                        <img class="line-shape" src="/images/shape/line-s1.png" alt="Virtuf-HasTech">
                        <nav class="widget-menu-wrap">
                            <ul class="nav-menu nav">
                                <li><nuxt-link to="/">Group Profile</nuxt-link></li>
                                <li><nuxt-link to="/">Vision & Values</nuxt-link></li>
                                <li><nuxt-link to="/">Company History</nuxt-link></li>
                                <li><nuxt-link to="/">Careers</nuxt-link></li>
                                <li><nuxt-link to="/">Winning Awards</nuxt-link></li>
                                <li><nuxt-link to="/">Sustainability</nuxt-link></li>
                            </ul>
                        </nav>
                    -->

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
                                <p>© 2024 Cyber Media Studio </p>
                            </div>
                        </div>
                        <div class="col-md-6 order-1 order-md-2">
                            <div class="widget-social-icons">
                                <a href="https://facebook.com/cybermediastudio"><i class="icofont-facebook"></i></a>
                                <a href="https://instagram.com/cybermediastudio"><i class="icofont-instagram"></i></a>
                                <a href="https://youtube.com/@cybermediastudio"><i class="icofont-youtube"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>