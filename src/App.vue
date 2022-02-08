<template>
  
  
  <div id="app">
    
    <header-box :navbar = "navbar" />
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
import SummaryAreas from "./components/SummaryAreas.vue";
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
  },
  data() {
    return {
      // HEADER-BOX: NAVBAR MENU
      navbar: [
        {
          id: "1",
          label: "Home",
          url: "#"
        },
        {
          id: "2",
          label: "Shop",
          url: "#"
        },
        {
          id: "3",
          label: "Products",
          url: "#"
        },
        {
          id: "4",
          label: "Categories",
          url: "#"
        },
        {
          id: "5",
          label: "News",
          url: "#"
        },
        {
          id: "6",
          label: "Elements",
          url: "#"
          },
          ]
    }}
}
</script>

<style lang="scss">
@import './style/common.scss';

</style>
