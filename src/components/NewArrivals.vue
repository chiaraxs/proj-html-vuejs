<template>
    <div class="container-fluid">
        <div class="container mt-5">
            
            <div class="text-center">
                
                <div class="d-flex justify-content-center align-items-center">
                    
                    <!-- DIV VUOTO PER BORDI DIVISORI -->
                    <div class="border_bottom me-5"></div>
                    <!-- / DIV VUOTO PER BORDI DIVISORI -->
                    
                    <!-- TITLE -->
                    <h1>New Arrivals</h1>
                    <!-- / TITLE -->

                    <!-- DIV VUOTO PER BORDI DIVISORI -->
                    <div class="border_bottom ms-5"></div>
                    <!-- / DIV VUOTO PER BORDI DIVISORI -->

                </div>

                <!-- DETAILS -->
                <p class="text-muted">Brand new products from top designers</p>
                <!-- / DETAILS -->

            </div>
                    
                    
            <!-- OUTFITS CONTAINER -->
            <div class="row row-cols-5 mt-5">

                <!-- OUTFIT 1 -->
                <div class="col">
                    
                    <div class="container-outfit">

                        <!-- SHOW -->
                        <div id="show">
                            <img src="../assets/img/modern_love_tee-200x260.jpg" alt="">
                        </div>
                        <!-- / SHOW -->

                        <!-- HIDDEN -->
                        <div id="hidden">
                            
                            <div class="text-light fw-bold text-center py-4">
                                <h4>Modern Love Tee</h4>
                                <p>Women T-Shirt
                                    <br>
                                    $68
                                </p>
                            
                            </div>
                            
                            <div class="text-light text-center fw-bold mt-5">
                                <span>Add to cart <i class="fas fa-shopping-cart me-3"></i> 
                                Details <i class="fas fa-info mx-1"></i></span>
                            </div>
                                
                        </div>
                        <!-- / HIDDEN -->
                        
                    </div>
                   
                        
                </div>
                <!-- / OUTFIT 1  -->

                <!-- OUTFIT 2 -->
                <div class="col">
                    
                    <div class="container-outfit">
                        <img class="img-fluid" src="../assets/img/hipster_black_top-200x260.jpg" alt="">
                    </div>
                    
                </div>
                <!-- / OUTFIT 2 -->
                        
                <!-- OUTFIT 3 -->
                <div class="col">

                    <div class="container-outfit">
                        <img class="img-fluid" src="../assets/img/black_leather_suit-200x260.jpg" alt="">
                    </div>
                    
                </div>
                <!-- / OUTFIT 3 -->
                            
                <!-- OUTFIT 4 -->
                <div class="col">
                    
                    <div class="container-outfit">
                        <img class="img-fluid" src="../assets/img/spring_printed_dress-200x260.jpg" alt="">
                    </div>
                    
                </div>
                <!-- / OUTFIT 4 -->

                <!-- OUTFIT 5 -->
                <div class="col">
                    
                    <div class="container-outfit">
                        <img class="img-fluid" src="../assets/img/black_elegant_leather_jacket-200x260.jpg" alt="">
                    </div>
                    
                </div>
                <!-- / OUTFIT 5 -->

                        
            </div>
            <!-- / OUTFITS CONTAINER  -->

            
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.border_bottom{
    border-bottom: 1px solid $edward-color;
    width: 400px;
}

#hidden{
    width: 200px;
    height: 260px;
    display: none;
    background: rgb(103,122,215);
    background: linear-gradient(169deg, rgba(103,122,215,1) 0%, rgba(225,70,252,0.3536765047816002) 100%); 
}

#show{
    position: absolute;
    z-index: 0;
}

.container-outfit{
    
    &:hover {
        #show{
            -webkit-transition: opacity 1s ease-in-out;
            -moz-transition: opacity 1s ease-in-out;
            -ms-transition: opacity 1s ease-in-out;
            -o-transition: opacity 1s ease-in-out;
            transition: opacity 1s ease-in-out;
            opacity: 0.1;
        }

        #hidden{
            display: block;
        }
    }
}


</style>