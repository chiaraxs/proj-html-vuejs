<template>
    <div class="container-fluid container-footer">
        <div class="container">
            <div class="row">
                
                <!-- CONTACTS -->
                <div class="col-3">
                    <div class="logo-box mt-5">
                        <img class="logo" src="../assets/img/classic_shop_logo_footer.png" alt="">
                    </div>

                    <div class="list-container mt-5">
                        <ul class="list-unstyled" v-for="item in footerContacts" :key="item" >
                            <li><a class="text-secondary text-decoration-none"> {{item.addres}} </a></li>
                            <li><a class="text-secondary text-decoration-none"> {{item.city}} </a></li>
                            <li><a class="text-secondary text-decoration-none"> Phone: {{item.phoneNumber}} </a></li>
                            <li><a class="text-secondary text-decoration-none"> Email: {{item.mail}} </a></li>
                            <li><a class="text-secondary text-decoration-none"> Web: {{item.web}} </a></li>
                        </ul>
                    </div>
                    
                    <div class="d-flex text-light pt-3">
                    
                        <i class="fab fa-facebook-f mx-2 "></i>
                        <i class="fab fa-twitter mx-2"></i>
                        <i class="fab fa-instagram mx-2"></i>
                        <i class="fab fa-youtube mx-2"></i>
                    
                    </div>

                </div>
                <!-- / CONTACTS -->

                <!-- TOP RATED PRODUCTS -->
                <div class="col-3">

                    <p class="text-uppercase text-muted mt-5">top rated products</p>

                    <div class="list-container mt-5">
                        <div class="list-unstyled" v-for="item in topRatedProducts" :key="item" >
                            
                            <img :src="item.image">
                            
                            <li>
                                <a class="text-secondary text-decoration-none"> {{item.article}} </a>
                            </li>

                            <li>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </li>
                            
                            <li>
                                <a class="text-secondary text-decoration-none"> {{item.price}} </a>
                            </li>
                            
                            <hr class="text-muted">
                        
                        </div>
                    </div>
                </div>
                <!-- / TOP RATED PRODUCTS -->
                
                
                <!-- RECENT POSTS -->
                <div class="col-3">

                    <p class="text-uppercase text-muted mt-5">recents posts</p>
                    
                    <div class="list-container mt-5">
                        <ul class="list-unstyled" v-for="item in recentPosts" :key="item" >
                            <li>
                                <i class="fas fa-chevron-right text-light me-2"></i>
                                <a class="text-secondary text-decoration-none"> {{item.post}} </a>
                                <hr class="text-muted">
                            </li>
                        </ul>
                    </div>
                </div>
                <!-- / RECENT POSTS -->


                <!-- TAGS -->
                <div class="col-3 column-tags ">
                    
                    <p class="text-uppercase text-muted mt-5">TAGS</p>

                    <div class="container-tag d-inline-flex text-light fs-6 mx-1 my-1 px-2" v-for="item in tagsList" :key="item">
                        {{item.tag}} 
                    </div>
                </div>
                <!-- / TAGS -->
                
            </div>
        </div>
    </div>
</template>


<script>
export default {
    props: {
       footerContacts: Array,
       topRatedProducts: Array,
       recentPosts: Array,
       tagsList: Array, 
    }
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.container-footer{
    max-height: 750px;
    background-color: $darks-late-gray-bg;

    .logo-box{
        width: 200px;
        

        img{
            width: 100%;
        }
    }

    .container-tag{
        border: 1px solid $edward-color;
        cursor: pointer;

        &:hover{
        background-color: $shocking-color;
    }

    }

}
</style>