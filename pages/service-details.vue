<template>
    <div class="service-details-page-wrapper">
        <Header />
        <OffCanvasMobileMenu />
        <PageTitle title="Business Consulting" breadcrumbTitle="Service Details" />
        <ServiceDetailsWrapper />
        <ContactDevider />
        <Footer />
    </div>
</template>

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),
            PageTitle: () => import('@/components/PageTitle'),
            ServiceDetailsWrapper: () => import('@/components/ServiceDetailsWrapper'),
            ContactDevider: () => import('@/components/ContactDevider'),
            Footer: () => import('@/components/Footer'),
        },
    };
</script>


