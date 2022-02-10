<template>
    <div class="container-fluid">
        <div class="container mt-5">
            
            <div class="text-center">
                
                <div class="d-flex justify-content-center align-items-center">
                    <!-- DIV VUOTO CON BORDER BOTTOM -->
                    <div class="border_bottom me-5"></div>
                    <!-- / DIV VUOTO CON BORDER BOTTOM -->
                    
                    <!-- TITLE -->
                    <h1>Best Seller</h1>
                    <!-- / TITLE -->

                    <!-- DIV VUOTO CON BORDER BOTTOM -->
                    <div class="border_bottom ms-5"></div>
                    <!-- / DIV VUOTO CON BORDER BOTTOM -->

                </div>

                <!-- DETAILS -->
                <p class="text-muted">Must have products from our top sellers</p>
                <!-- / DETAILS  -->

            </div>
                    
                    
            <!-- OUTFITS CONTAINER -->
            <div class="row row-cols-5 mt-5">

                <!-- OUTFIT 1 -->
                <div class="col">
                    
                    <div class="container-outfit">
                        <img class="img-fluid" src="../assets/img/spring_printed_dress-400x520.jpg" alt="">
                    </div>
                   
                </div>
                <!-- / OUTFIT 1  -->

                <!-- OUTFIT 2 -->
                <div class="col">
                    
                    <div class="container-outfit">
                        <img class="img-fluid" src="../assets/img/modern_love_tee-400x520.jpg" alt="">
                    </div>
                    
                </div>
                <!-- / OUTFIT 2 -->
                        
                <!-- OUTFIT 3 -->
                <div class="col">

                    <div class="container-outfit">
                        <img class="img-fluid" src="../assets/img/black_leather_jacket-400x520.jpg" alt="">
                    </div>
                    
                </div>
                <!-- / OUTFIT 3 -->
                            
                <!-- OUTFIT 4 -->
                <div class="col">
                    
                    <div class="container-outfit">
                        <img class="img-fluid" src="../assets/img/black_elegant_leather_jacket-400x520.jpg" alt="">
                    </div>
                    
                </div>
                <!-- / OUTFIT 4 -->

                 <!-- OUTFIT 5 -->
                <div class="col">
                    
                    <div class="container-outfit">
                        <img class="img-fluid" src="../assets/img/hipster_black_top-400x520.jpg" alt="">
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
</style>