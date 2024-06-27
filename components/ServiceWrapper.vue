<template>
    <section class="service-area">
        <div class="container">
            <div class="row icon-box-style1">
                <div class="col-md-6 col-lg-4" data-aos="fade-up" data-aos-duration="1100" v-for="(service, index) in services" :key="index">
                    <ServiceItem :service="service" />
                </div>
            </div>
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
                        title: "SERVICE WRAPPER",
                        desc: "Where is this Service Wrapper?"
                    },
                    {
                        icon: "/images/icons/s2.png",
                        title: "Market Analysis",
                        desc: "Where is this Service Wrapper?"
                    },
                    {
                        icon: "/images/icons/s3.png",
                        title: "Brand Identity",
                        desc: "Where is this Service Wrapper?"
                    },
                    {
                        icon: "/images/icons/s4.png",
                        title: "Business Consultation",
                        desc: "Where is this Service Wrapper?"
                    },
                    {
                        icon: "/images/icons/s5.png",
                        title: "SEO Marketing",
                        desc: "Where is this Service Wrapper?"
                    },
                    {
                        icon: "/images/icons/s6.png",
                        title: "UX & UI Design",
                        desc: "Where is this Service Wrapper?"
                    },
                ]
            }
        },
    };
</script>