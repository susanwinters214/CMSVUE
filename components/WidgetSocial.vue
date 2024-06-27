<template>
    <div class="widget" data-aos="fade-up" data-aos-duration="1200">
        <h3 class="widget-title">Share Now.</h3>
        <div class="separator-line">
            <img class="me-1" src="/images/shape/line-s2.png" alt="Image-HasTech">
            <img src="/images/shape/line-s1.png" alt="Image-HasTech">
        </div>
        <div class="widget-social">
            <div class="social-item" v-for="(social, index) in socialList" :key="index">
                <a :href="social.url">
                    <div class="icon">
                        <i :class="social.iconName"></i>
                    </div>
                    <span>{{ social.title }}</span>
                </a>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                socialList: [
                    {
                        iconName: "icofont-facebook",
                        title: "Facebook",
                        url: "https://facebook.com/cybermediastudio.com"
                    },
                    {
                        iconName: "icofont-instagram",
                        title: "instagram",
                        url: "https://instagram.com/cybermediastudio.com"
                    },
                    {
                        iconName: "icofont-youtube",
                        title: "youtube",
                        url: "https://youtube.com/@cybermediastudio.com"
                    }
                ]
            }
        },
    };
</script>
