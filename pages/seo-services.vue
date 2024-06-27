<template>
    <div class="service-details-page-wrapper">
        <Header />
        <OffCanvasMobileMenu />
        <PageTitle title="Search Engine Optimization" breadcrumbTitle="SEO" />
        <ServiceDetailsWrapper />
      
        <Footer />
    </div>
</template>

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),
            PageTitle: () => import('@/components/PageTitle'),
            ServiceDetailsWrapper: () => import('@/components/SEOpricegrid'),
           
            Footer: () => import('@/components/Footer'),
        },
    };
</script>


