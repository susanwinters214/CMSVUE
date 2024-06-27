<template>
    <section class="team-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 m-auto">
                    <div class="section-title text-center" data-aos="fade-up" data-aos-duration="1000">
                        <h2 class="title">Certified by Google</h2>
                        <div class="separator-line mt-14">
                            <img class="me-1" src="/images/shape/line-s2.png" alt="Images">
                            <img src="/images/shape/line-s1.png" alt="Images">
                        </div>
                        <div class="desc">
                            <p class="mt-21">Susan Winters has obtained many Google Certifications. Shown here are certifications for UX/UI Design, Technical Suppport and Digital Marketing and Ecommerce.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-4">  
                  <!--BOX UX/UI Design-->  
                            <section class="team-member">
                                      
                                     <div class="content">
                                        <div class="member-info">
                                            <a href="/images/about/Google-Certification-UX-Design.png"><img src="/images/about/Google-Certification-UX-Design.png" alt="Google Certification UX Design"></a><br />
                                            <h4 class="name">UX/UI Design</h4>
                                             <h6 class="designation">Google</h6>                                            
                                        </div>
                                    </div>
                                    <div class="shape-style">
                                        <img class="shape-style1" src="/images/shape/8.png" alt="Image">
                                        <img class="shape-style2" src="/images/shape/9.png" alt="Image">
                                        <img class="shape-style3" src="/images/shape/10.png" alt="Image">
                                    </div>

                                </section>
                  </div>

                <div class="col-lg-4">  
                  <!--BOX Digital Marketing-->
                                <section class="team-member">
                                         <a href="/images/about/Google-Digital-Marketing-Ecommerce.jpg"><img src="/images/about/Google-Digital-Marketing-Ecommerce.jpg" alt="Google Digital Marketing Ecommerce"></a><br />
                             
                                    <div class="content">
                                        <div class="member-info">
                                            <div class="separator-line">
                                                <img src="/images/shape/line-s1.png" alt="Images">
                                            </div>
                                              <h4 class="name">Digital Marketing</h4>
                                            <h6 class="designation">Google</h6>            
                                            
                                            
                                        </div>
                                    </div>
                                    <div class="shape-style">
                                        <img class="shape-style1" src="/images/shape/8.png" alt="Image">
                                        <img class="shape-style2" src="/images/shape/9.png" alt="Image">
                                        <img class="shape-style3" src="/images/shape/10.png" alt="Image">
                                    </div>
                                </section>
                                </div>
                <div class="col-lg-4">  
                  <!--BOX Technical Support -->            
                                <section class="team-member">
                                      
                                     <div class="content">
                                        <div class="member-info">
                                             <a href="/images/about/Google-Certification-Technical-Support.png"><img src="/images/about/Google-Certification-Technical-Support.png" alt="Images"></a><br />
                                             <h4 class="name">Technical Support</h4>
                                             <h6 class="designation">Google</h6>                                            
                                        </div>
                                    </div>
                                    <div class="shape-style">
                                        <img class="shape-style1" src="/images/shape/8.png" alt="Image">
                                        <img class="shape-style2" src="/images/shape/9.png" alt="Image">
                                        <img class="shape-style3" src="/images/shape/10.png" alt="Image">
                                    </div>

                                </section>
                          
                     
                   
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    import { Swiper, SwiperSlide } from "swiper/vue"

    export default {
        components: {
            Swiper,
            SwiperSlide
        },
        data() {
            return {
                swiperOptions: {
                    breakpoints: {
                        992:{
                            slidesPerView : 3
                        },
                        768:{
                            slidesPerView : 2,
                            centeredSlides: false
                        },
                        0:{
                            slidesPerView : 1
                        }
                    }
                }
            }
        },
    };
</script>