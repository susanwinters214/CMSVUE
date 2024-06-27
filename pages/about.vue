<template>
    <div class="about-page-wrapper">
        <Header />
        <OffCanvasMobileMenu />
        <PageTitle title="About Us" breadcrumbTitle="About" />
        
        <AboutTwo /> <!-- About Susan section -->
        <AboutCertifications /> <!-- susan's certifications -->
        <AboutSEOexperts /> <!-- photos of SEO experts -->
    
        <Footer />
    </div>
</template>

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),
            PageTitle: () => import('@/components/PageTitle'),
           
            AboutTwo: () => import('@/components/AboutTwo'),
            AboutCertifications: () => import('@/components/AboutCertifications'),
            AboutSEOexperts: () => import('@/components/AboutSEOexperts'),
         
            Footer: () => import('@/components/Footer'),
        }
    }
</script>


