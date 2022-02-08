<template>
  
  
  <div id="app">
    
    <header-box />
    <hero-box />
    <featured-products />
    <collections-box />
    <best-seller />
    <free-shipping />
    <new-arrivals />
    <customers-review />
    <our-blog />
    <summary-areas />
    <brand-logs />
    <subscribe-box />
    <footer-box />
    <payment-type />
    

  </div>



</template>

<script>
import HeaderBox from "./components/HeaderBox.vue";
import HeroBox from "./components/HeroBox.vue";
import FeaturedProducts from "./components/FeaturedProducts.vue";
import CollectionsBox from "./components/CollectionsBox.vue";
import BestSeller from "./components/BestSeller.vue";
import FreeShipping from "./components/FreeShipping.vue";
import NewArrivals from "./components/NewArrivals.vue";
import CustomersReview from "./components/CustomersReview.vue";
import OurBlog from "./components/OurBlog.vue";
import SummaryAreas from "./components/SummaryAreas";
import BrandLogs from "./components/BrandLogs.vue";
import SubscribeBox from "./components/SubscribeBox.vue";
import FooterBox from "./components/FooterBox.vue";
import PaymentType from "./components/PaymentType.vue";


export default {
  name: 'App',
  components: {
    HeaderBox,
    HeroBox,
    FeaturedProducts,
    CollectionsBox,
    BestSeller,
    FreeShipping,
    NewArrivals,
    CustomersReview,
    OurBlog,
    SummaryAreas,
    BrandLogs,
    SubscribeBox,
    FooterBox,
    PaymentType,
}
}
</script>

<style lang="scss">
@import './style/common.scss';

</style>
