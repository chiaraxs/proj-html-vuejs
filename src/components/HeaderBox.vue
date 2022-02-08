<template>
   
    <!-- CONTAINER HEADER-BOX -->
    <div class="container-header-box">

        <!-- PRE HEADHER - COMPONENTE A PARTE? -->
        <div class="container-fluid container-pre-header d-flex">
            <div class="container d-flex ps-5 pt-3">
                
                <i class="fab fa-facebook-f mx-2"></i>
                <i class="fab fa-twitter mx-2"></i>
                <i class="fab fa-instagram mx-2"></i>
                <i class="fab fa-youtube mx-2"></i>
            
            </div>
            
            <div class="container d-flex justify-content-end">
                <div class="shopping"> 
                    <p class="px-2 py-2">Shooping Cart</p>  
                </div>
               <div class="my-account"> 
                   <p class="px-2 py-2">My Account <i class="fas fa-chevron-down"></i></p> 
                </div>
               <div class="cart"> 
                   <p class="px-2 py-2 text-uppercase"><i class="fas fa-shopping-cart px-1 py-1 me-2"></i>Cart <i class="fas fa-chevron-down"></i></p> 
                </div>
            </div>
            
        </div>
        <!-- / PRE HEADHER -->
        
        <!-- NAVBAR -->
        <nav class="navbar container-fluid navbar-light bg-light d-flex justify-content-between">

            <!-- LOGO -->
            <div class="logo-container ms-5 py-2">
                <img src="@/assets/img/classic_shop_logo1x.png" alt="logo" >
            </div>
            <!-- / LOGO -->
                
            <!-- CONTAINER MENU-->
            <div class="container container-menu d-flex justify-content-center">
                   
                <!-- MENU LIST -->
                <ul class="d-flex list-unstyled ">
                    <li class="px-4" v-for="item in navbar" :key="item.id">
                        <a class="text-secondary text-decoration-none" :href="item.url"> {{item.label}} </a> 
                        <i class="fas fa-chevron-down"></i>
                    </li>
                </ul>
                <!-- / MENU LIST -->
            </div>       
            <!-- / CONTAINER MENU  -->
                
            <!-- CONTAINER BUTTON/ICON -->
            <div class="d-flex justify-content-end">
                <!-- BUTTON -->
                <button type="button" class="btn text-light text-uppercase rounded-pill mb-3 me-4 ">Shop now!</button>
                <!-- / BUTTON -->

                <!-- SEARCH LENS -->
                <a href="#"><i class="fas fa-search"></i></a>
                <!-- / SEARCH LENS -->
            </div>
            <!-- / CONTAINER BUTTON/ICON -->
                    
            
        
        </nav>
        <!-- / NAVBAR -->
    </div>
   <!-- / CONTAINER HEADER-BOX -->


</template>


<script>
export default {
    props: {
       navbar: Array,
    },
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.container-pre-header{
    border-bottom: 1px solid gray;

    .shopping, .my-account{
        border-right: 1px solid gray;
    }

    .fab, .fas{
        font-size: 20px;
    }

    .fa-chevron-down{
        font-size: 10px;
    }
}

a{
    color: gray;
}
.fa-chevron-down{
    font-size: 10px;
}

.fa-search{
    font-size: 25px;
}

button{
    background-color: $button-color;
}



</style>