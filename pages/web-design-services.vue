<template>
    <div class="portfolio-details-page-wrapper">
        <Header />
        <OffCanvasMobileMenu />

        <PageTitle title="Web Design Services" breadcrumbTitle="Web Design" />
         <WebDesignPriceGrid />
       <TechStack />

        <PortfolioDetailsWrapper />
         <BrandLogoSection /> <!--Logo Design--> 

         <!--WEBSITE PRICES-->
           <div id="websitePrices" style="height:100vm">

                <section class="service-area" id="webdesignprices">
                    <h3 style="text-align:center;padding-top:25px;">Web Design Prices:</h3>
                        <div class="container" style="text-align:center">
                          
                                    <div class="row">
                                        <div class="col-lg-4" style="padding-bottom:30px;">
                                            <div id="webprice1" class="content">
                                                <img src="/images/webdesign-995.png" alt="image">
                                                 <p style="text-align:center"><a target="_blank" href="https://buy.stripe.com/3csbMs6crerJcOA5kr">1-5 Page Website</a></p>
                                            </div>
                                        </div>
                                        <div id="webprice2" class="col-lg-4" style="padding-bottom:30px;">
                                            <div class="content">
                                                <img src="/images/webdesign-1595-deposit.png" alt="image">
                                                <p style="text-align:center"><a target="_blank" href="https://buy.stripe.com/3cs6s8dET6ZhbKwbIO">6-10 Page Website</a></p>
                                            </div>
                                        </div> 
                                        <div id="webprice3" class="col-lg-4" style="padding-bottom:30px;">                                            
                                            <div class="content">
                                                <img src="/images/webdesign-2495.png" alt="image">
                                            <p style="text-align:center"><a target="_blank" href="https://buy.stripe.com/aEU4k06crcjB9CobIQ">11-20 Page Website</a></p>
                                            </div>
                                        </div>
                                    </div>
                        </div>
                 </section>



         </div>
    
       
      <Footer />


    </div>
</template>

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),

            PageTitle: () => import('@/components/PageTitle'),

           
            TechStack: () => import('@/components/TechStack'), /* Tech Stack */
              
            PortfolioDetailsWrapper: () => import('@/components/PortfolioDetailsWrapper'),

            BrandLogoSection: () => import('@/components/BrandLogoSection'),/* Graphic Desing: logos */

           WebDesignPrices: () => import('@/components/WebDesignPrices'),/* WebDesignPrices */

           
            Footer: () => import('@/components/Footer'),
        },
    };
</script>


