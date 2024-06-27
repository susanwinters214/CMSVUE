<template>
    <div class="main-container">
        <Header />
        <OffCanvasMobileMenu />

        <HeroSlider /> <!--TOP OF PAGE PHOTO-->
        <HomeDigitalMarketing /> <!--Digital AI Section-->
        <HomeServices /><!--SERVICES Section-->

        <HomeFaqs /><!--FAQs Section-->

       
        <Footer />
    </div>
</template>

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),
            HeroSlider: () => import('@/components/HeroSlider'),  /*--Top Page Photo Section--*/
            HomeDigitalMarketing: () => import('@/components/HomeDigitalMarketing'),      /*--Digital AI Section--*/
            HomeServices: () => import('@/components/HomeFAQs'), /*-- SERVICES Section--*/
            HomeFaqs: () => import('@/components/HomeFAQs'),        /*-- FAQs Section--*/
            Footer: () => import('@/components/Footer'),
        }
    };
</script>


