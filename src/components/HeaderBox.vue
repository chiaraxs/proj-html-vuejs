<template>
   
    <!-- CONTAINER HEADER-BOX -->
    <div class="container-header-box">

        <!-- PRE HEADHER - COMPONENTE A PARTE? -->
        <div class="container-fluid">
            <div class="container container-pre-header d-flex">
                <div class="d-flex ps-5 pt-3">
                    
                    <i class="fab fa-facebook-f mx-2"></i>
                    <i class="fab fa-twitter mx-2"></i>
                    <i class="fab fa-instagram mx-2"></i>
                    <i class="fab fa-youtube mx-2"></i>
                
                </div>
                
                <div class="container d-flex justify-content-end text-center">
                    <div class="shopping"> 
                        <p class="px-4 py-2">Shooping Cart</p>  
                    </div>
                <div class="my-account"> 
                    <p class="px-4 py-2">My Account <i class="fas fa-chevron-down"></i></p> 
                    </div>
                <div class="cart"> 
                    <p class="px-4 py-2 text-uppercase"><i class="fas fa-shopping-cart px-1 py-1 me-2"></i>Cart <i class="fas fa-chevron-down"></i></p> 
                    </div>
                </div>
                
            </div>
            
        </div>
        <!-- / PRE HEADHER -->
        
        <!-- NAVBAR -->
        <nav class="container d-flex justify-content-between mt-3">

            <!-- LOGO -->
            <div class="logo-container ms-5 py-2">
                <img src="@/assets/img/classic_shop_logo1x.png" alt="logo" >
            </div>
            <!-- / LOGO -->
                
            <!-- CONTAINER MENU-->
            <div class="container-menu">
                   
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
            <div class="container-button-icon">
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

.container-fluid{
    border-bottom: 1px solid gray;
    
 .container-pre-header{
     .shopping, .my-account{
        border-right: 1px solid gray;

        p{
         color: $text-primary-color;
        }
    }

    .fab, .fas{
        font-size: 20px;
    }

    .fa-chevron-down{
        font-size: 10px;
    }

    .cart{
        width: 200px;
        background-color: rgb(241, 241, 241);
    }

 } 

    
}

a{
    color: $text-primary-color;
}
.fa-chevron-down{
    font-size: 10px;
}

.fa-search{
    font-size: 20px;
}

button{
    background-color: $button-color;
        &:hover{
                background-color: $button-hover;
            }
}



</style>