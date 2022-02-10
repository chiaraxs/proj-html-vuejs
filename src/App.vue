<template>
  
  
  <div id="app">
    
    <header-box :navbar = "navbar" logo="/classic_shop_logo1x.png" /> 
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
    <footer-box
    logo="/classic_shop_logo_footer.png"
    :footerContacts = "footerContacts" 
    :topRatedProducts = "topRatedProducts"  
    :recentPosts = "recentPosts"
    :tagsList = "tagsList"  />
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
      ],
      // FOOTER CONTACTS
      footerContacts: [
        {
          address: "12345 North Main Street,",
          city: "New York, NY 55555",
          phoneNumber: "1.800.555.6789",
          mail: "info@compani.com",
          web: "Theme-fusion.com",
        }
      ],
      // TOP RATED PRODUCTS
      topRatedProducts: [
        {
          article: "Leather Gloves",
          image: "https://thumbs2.imgbox.com/ad/dd/IVFGCvIi_t.jpg",
          price: "$45",
        },

        {
          article: "Black Leather Jacket",
          image: "https://thumbs2.imgbox.com/5b/03/QGJ1tzQo_t.jpg",
          price: "$235",
        },

        {
          article: "Spring Printed Dress",
          image: "https://thumbs2.imgbox.com/db/7c/jf9rkkfH_t.jpg",
          price: "$47",
        }
      ],
      // RECENT POSTS
      recentPosts: [
        {
          id: "1",
          post: "Aenean lobortis sapien enim viverra",
        },
        {
          id: "2",
          post: "Duis ac massa semper maximus",
        },
        {
          id: "3",
          post: "Nunc fermint nulla eu justo sem id",
        },
        {
          id: "4",
          post: "Aliquam posuere magna eget nibh",
        },
        {
          id: "5",
          post: "Cras ac nulla ac consecte rutrum",
        },
        {
          id: "6",
          post: "Fusce mattis nunc ut aliquam",
        },
      ],
      // TAGS
      tagsList: [
        {
          id: "1",
          tag: "Black"
        },
        {
          id: "2",
          tag: "boots"
        },
        {
          id: "3",
          tag: "Brown"
        },
        {
          id: "4",
          tag: "Casual"
        },
        {
          id: "5",
          tag: "D&G"
        },
        {
          id: "6",
          tag: "Fabric"
        },
        {
          id: "7",
          tag: "flowers"
        },
        {
          id: "8",
          tag: "Grey"
        },
        {
          id: "9",
          tag: "hat"
        },
        {
          id: "1o",
          tag: "Hipster"
        },
        {
          id: "11",
          tag: "lines"
        },
        {
          id: "12",
          tag: "multi-purpose"
        },
        {
          id: "13",
          tag: "New York"
        },
        {
          id: "14",
          tag: "Outdoors"
        },
        {
          id: "15",
          tag: "red"
        },
        {
          id: "16",
          tag: "responsive"
        },
        {
          id: "17",
          tag: "summer"
        },
        {
          id: "18",
          tag: "sweater"
        },
        {
          id: "19",
          tag: "Travel"
        },
        {
          id: "20",
          tag: "Warm"
        },
        {
          id: "21",
          tag: "White"
        },
        {
          id: "22",
          tag: "winter"
        },
      ],
  }}
}
</script>

<style lang="scss">
@import './style/common.scss';

</style>
