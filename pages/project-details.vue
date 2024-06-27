<template>
    <div class="portfolio-details-page-wrapper">
        <Header />
        <OffCanvasMobileMenu />

        <PageTitle title="Web Design" breadcrumbTitle="Web Design" />
 <FunFactOne />
        <PortfolioDetailsWrapper />
         <BrandLogoSection />
        <ContactDevider />
        <Footer />
    </div>
</template>

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),
            FunFactOne: () => import('@/components/FunFactOne'),
               BrandLogoSection: () => import('@/components/BrandLogoSection'),
            PageTitle: () => import('@/components/PageTitle'),
            PortfolioDetailsWrapper: () => import('@/components/PortfolioDetailsWrapper'),
            ContactDevider: () => import('@/components/ContactDevider'),
            Footer: () => import('@/components/Footer'),
        },
    };
</script>


