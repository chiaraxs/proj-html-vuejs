<template>
    
    <!-- HEADER -->
    <header class="sticky-top">
        <!-- CONTAINER HEADER-BOX -->
        <div class="container-header-box">

            <!-- PRE HEADHER -->
            <div class="container-fluid">
                <div class="container container-pre-header d-flex">
                    
                    <!-- SX -->
                    <div class="d-flex ps-5 pt-3">
                        
                        <i class="fab fa-facebook-f mx-2 "></i>
                        <i class="fab fa-twitter mx-2"></i>
                        <i class="fab fa-instagram mx-2"></i>
                        <i class="fab fa-youtube mx-2"></i>
                    
                    </div>
                    <!-- / SX -->

                    <!-- DX -->
                    <div class="container d-flex justify-content-end">
                        <div class="shopping"> 
                            <p class="px-4 py-2">Shooping Cart</p>  
                        </div>
                    <div class="my-account"> 
                        <p class="px-4 py-2">My Account <i class="fas fa-chevron-down"></i></p> 
                        </div>
                    <div class="cart"> 
                        <p class="px-4 py-2 text-uppercase"><i class="fas fa-shopping-cart py-1 px-1 me-2"></i>Cart <i class="fas fa-chevron-down px-1"></i></p> 
                        </div>
                    </div>
                    <!-- / DX -->

                </div>
                
            </div>
            <!-- / PRE HEADHER -->
            
            <!-- NAVBAR -->
            <nav class="container d-flex justify-content-between mt-3">

                <!-- LOGO -->
                <div class="logo-container ms-5 py-2">
                    <img :src="`/img${logo}`" >  
                </div>
                <!-- / LOGO -->
                    
                <!-- CONTAINER MENU-->
                <div class="container-menu">
                    
                    <!-- MENU LIST -->
                    <ul class="d-flex list-unstyled ">
                        <li class="px-4" v-for="item in navbar" :key="item.id">
                            <a class="text-secondary text-decoration-none" :href="item.url"> {{item.label}} </a> 
                            <i class="fas fa-chevron-down px-1"></i>
                        </li>
                    </ul>
                    <!-- / MENU LIST -->
                </div>       
                <!-- / CONTAINER MENU  -->
                    
                <!-- CONTAINER BUTTON/ICON -->
                <div class="container-button-icon">
                    <!-- BUTTON -->
                    <button type="button" class="btn text-light text-uppercase rounded-pill mb-3 me-4">Shop now!</button>
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

    </header>
    <!-- / HEADER -->

</template>


<script>
export default {
    props: {
        logo: String,
        navbar: Array,
    },
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

header{
    background-color: $white-color;
}
.container-fluid{
    border-bottom: 1px solid $edward-color;
    
    .container-pre-header{
        .shopping, .my-account{
            border-right: 1px solid $edward-color;

            p{
            color: $shark-color;
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
            background-color: $misty-rose-bg;
        }
    }  
}

a{
    color: $shark-color;
}

.fa-chevron-down{
    font-size: 10px;
}

.fa-search{
    font-size: 20px;
}

button{
    background-color: $havelock-blue-color;
        
    &:hover{
        background-color: $shocking-color;
    }
}


</style>