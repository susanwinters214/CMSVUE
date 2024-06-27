<template>
    <section class="service-area service-default-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 col-xl-6 m-auto">
                    <div class="section-title text-center" data-aos="fade-up" data-aos-duration="1000">
                        <h2 class="title">Cyber Media Studio Services</h2>
                        <div class="separator-line mt-14">
                            <img class="me-1" src="/images/shape/line-s2.png" alt="Images">
                            <img src="/images/shape/line-s1.png" alt="Images">
                        </div>
                        <div class="desc">
                            <p class="mt-21"></p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row icon-box-style1">
                <div class="col-md-6 col-lg-4" data-aos="fade-up" data-aos-duration="1100" v-for="(service, index) in services" :key="index">
                    <ServiceItem :service="service" />
                </div>
            </div>
        </div>
        <div class="layer-shape">
            <img class="layer-shape-one" src="/images/shape/6.png" alt="shape">
            <img class="layer-shape-two" src="/images/shape/7.png" alt="shape">
        </div>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                services: [
                    {
                        icon: "/images/icons/s1.png",
                        title: "Web Development",
                        desc: "We can provide you with a website made with HTML, CSS and JavaScript or a WordPress site designed to help you increase brand recognition, customer loyalty, and your bottom line."
                    },
                    {
                        icon: "/images/icons/s5.png",
                        title: "SEO Marketing",
                        desc: "Search Engine Optimization is a service you know you need, but you may not understand. We can take care of your Technical SEO, Backlink Strategy, LOCAL SEO, Schema Tags, Meta Descriptions & more."
                    },

                    {
                        icon: "/images/icons/s2.png",
                        title: "Keyword Research",
                        desc: "We assist you in selecting keywords for your site so that your content has a better chance of ranking on Google. We will help you steer clear of generic keywords and instead target long-tail keywords."
                    },

 {
                        icon: "/images/icons/s3.png",
                        title: "Brand Identity",
                        desc: "Branding includes your company’s colors, fonts, and tone. It serves as the binding agent in an efficient marketing strategy and as the cornerstone of your marketing plan."
                    },
                    {
                        icon: "/images/icons/s4.png",
                        title: "Website Maintenance",
                        desc: "Wesites need regular maintenance, especially WordPress websites! We make sure your website, plugins and themes are kept updated."
                    },
                    {
                        icon: "/images/icons/s5.png",
                        title: "Sitemap Architecture",
                        desc: "The order in which you layout your website plays a huge role in how your website will rank. We can set up your sitemap.xml, robots.txt and web.config files."
                    },
                 
                ]
            }
        },
    };
</script>