<template>
    <section class="testimonial-area testimonial-default-area">
        <div class="container">
            <div class="row">     <!---Testimonial ONE VUE---->
                <div class="col-lg-5 col-xl-5 md-text-center">
                    <div class="shape-layer tilt-animation" data-aos="fade-up" data-aos-duration="1100">
                        <img src="/images/about/seo-experts.jpg" alt="Virtuf-HasTech">
                    </div>
                </div>
                <div class="col-lg-7 col-xl-7">
                    <div class="section-title xs-text-center" data-aos="fade-up" data-aos-duration="1000">
                        <div class="subtitle-content xs-d-i-flex">
                            <img src="/images/shape/line1.png" alt="Virtuf-HasTech">
                            <h5>SEO Experts</h5>
                        </div>
                        <h2 class="title">Susan learned SEO from <span>Google experts.</span></h2>
                        <div class="separator-line">
                            <img src="/images/shape/line1.png" alt="Virtuf-HasTech">
                            <img src="/images/shape/line2.png" alt="Virtuf-HasTech">
                        </div>
                    </div>
                    <div class="testimonial-content md-pl-0 pl-lg-30 pl-70" data-aos="fade-up" data-aos-duration="1100">
                        <div class="testimonial-slider-content position-relative">
                            <div class="testimonial-slider-container">
                                <swiper
                                    :speed="1000"
                                    :navigation="testimonialSlider.navigation"
                                >
                                    <swiper-slide class="testimonial-single" v-for="(testimonial, index) in testimonials" :key="index">
                                        <div class="client-content">
                                            <p>{{ testimonial.desc }}</p>
                                            <img class="quote-icon" src="/images/icons/quote-icon.png" alt="Icon">
                                        </div>
                                        <div class="client-info">
                                            <img class="shape-line-img" src="/images/shape/line1.png" alt="Virtuf-HasTech">
                                            <a :href="testimonial.url" target="_blank"><h4 class="name">{{ testimonial.name }}</h4></a>
                                            <h6 class="designation">{{ testimonial.designation }}</h6>
                                        </div>
                                        <div class="icon-box">
                                            <img :src="testimonial.imgSrc" :alt="testimonial.name">
                                        </div>
                                    </swiper-slide>
                                </swiper>
                                <!-- Add Arrows -->
                                <div class="swiper-button-next"><i class="icofont-long-arrow-up"></i></div>
                                <div class="swiper-button-prev"><i class="icofont-long-arrow-down"></i></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    import { Swiper, SwiperSlide } from "swiper/vue"
    import SwiperCore, { Navigation } from 'swiper/core'
    SwiperCore.use([Navigation])

    export default {
        components: {
            Swiper,
            SwiperSlide
        },
        data() {
            return {
                testimonialSlider: {
                    navigation: {
                        nextEl: '.testimonial-slider-container .swiper-button-next',
                        prevEl: '.testimonial-slider-container .swiper-button-prev',
                    }
                },

                testimonials: [
                    {
                        name: "Matt Cutts",
                        designation: "Former head of the webspam team at Google",
                        imgSrc: "/images/icons/s5.png",
                        desc: "Matt Cutts is a key figure in communicating updates and best practices related to Google's search algorithm.",
                         url: 'https://www.linkedin.com/in/mattcutts/',
                    },
                    {
                        name: "Danny Sullivan:",
                        designation: "Marketing Consultant",
                        imgSrc: "/images/icons/s5.png",
                        desc: "Danny Sullivan is instrumental in educating the public about search engines and SEO.",
                         url: 'https://www.linkedin.com/in/dannysullivan/',
                    },
                    {
                        name: "Gary Illyes",
                        designation: "Webmaster trends analyst at Google",
                        imgSrc: "/images/icons/s5.png",
                        desc: "Gary Illyes provides insights and guidance on Google's search features and updates, helping webmasters understand how to optimize their sites for better search performance.",
                        url: 'https://www.linkedin.com/in/garyillyes/',
                    },
                ]
            }
        },
    };
</script>
