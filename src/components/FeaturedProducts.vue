<template>
    <div class="container-fluid">
        <div class="container mt-5">
            
            <div class="text-center">
                <div class="d-flex justify-content-center align-items-center">
                    <div class="border_bottom me-5"></div>
                    <h1>Featured Products</h1>
                    <div class="border_bottom ms-5"></div>
                </div>
                
                <p class="text-muted">Must have products from our top sellers</p>
            </div>
                    
                
            <!-- BUTTONS -->
            <div class="mt-4 justify-content-center d-flex">
                    
                <button type="button" class="btn btn-light border border-secondary px-5 py-2 fw-bold">Men</button>
                <button type="button" class="btn btn-light border border-secondary px-5 py-2 fw-bold">Women</button>
                <button type="button" class="btn btn-light border border-secondary px-5 py-2 fw-bold">Accessories</button>
                
            </div>  
             <!-- / BUTTONS -->
                    
            <!-- OUTFITS CONTAINER -->
            <div class="row mt-5">

                <!-- OUTFIT 1 HOVER -->
                <div class="col-3">
                    
                    <div class="container-outfit">
                        
                        <div id="show">
                            <img class="mb-2" src="../assets/img/black_elegant_leather_jacket-400x520.jpg" alt="">
                        </div>

                        <div id="hidden">
                            <div class="container-icon d-flex align-items-center justify-content-center">
                                <i class="fas fa-check-double"></i>
                            </div>
                        </div>
                        
                        
                        <div>
                            <span class="fw-bold">Black Leather Jacket</span>
                            <br>
                            <span class="text-muted">Men, Jacktes, Jeans</span>
                            <br>
                            <span class="text-decoration-line-through text-primary me-2">$235</span> <span class="text-primary">$200</span>
                        </div>
                        
                    </div>
                   
                        
                </div>
                <!-- / OUTFIT 1 HOVER  -->

                <!-- OUTFIT 2 -->
                <div class="col-3">
                    
                    <div class="container-outfit">
                        <img class="mb-2" src="../assets/img/black_leather_suit-400x520.jpg" alt="">
                        <span class="fw-bold">Black Leather Suit</span>
                        <br>
                        <span class="text-muted">Men, Jacktes</span>
                        <br>
                        <span class="text-primary">$176</span>
                    </div>
                    
                        
                </div>
                <!-- / OUTFIT 2 -->
                        
                <!-- OUTFIT 3 -->
                <div class="col-3">

                    <div class="container-outfit">
                        <img class="mb-2" src="../assets/img/blue_jacket_and_white_stripe_tee-400x520.jpg" alt="">
                        <span class="fw-bold">Blue Jacket & Stripe Tee</span>
                        <br>
                        <span class="text-muted">Men, Jacktes, Suits</span>
                        <br>
                        <span class="text-primary">$580</span>
                    </div>
                    
                </div>
                <!-- / OUTFIT 3 -->
                            
                <!-- OUTFIT 4 -->
                <div class="col-3">
                    
                    <div class="container-outfit">
                        <img class="mb-2" src="../assets/img/modern_black_leather_suit-400x520.jpg" alt="">
                        <span class="fw-bold">Modern Black Leather Suit</span>
                        <br>
                        <span class="text-muted">Men, Jacktes</span>
                        <br>
                        <span class="text-primary">$96</span>
                    </div>
                    
                </div>
                <!-- / OUTFIT 4 -->

                        
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

button{
    background-color: $white-smoke-bg;
        
    &:hover{
        background-color: $edward-color;
    }
}

#hidden{
    width: 400px;
    height: 520px;
    display: none;
    background: rgb(103,122,215);
    background: linear-gradient(169deg, rgba(103,122,215,1) 0%, rgba(225,70,252,0.3536765047816002) 100%); 

    .container-icon{
        width: 50px;
        height: 50px;
        background-color: $black-bg;
        border-radius: 50%;
        position: absolute;
        margin-left: 150px;
        margin-top: 200px;
        .fa-check-double{
            color: $white-color;
    
        }
    }
   
}

#show{
    position: absolute;
    z-index:0;
}

.container-outfit{
    
    &:hover {
        #show{
            -webkit-transition: opacity 1s ease-in-out;
            -moz-transition: opacity 1s ease-in-out;
            -ms-transition: opacity 1s ease-in-out;
            -o-transition: opacity 1s ease-in-out;
            transition: opacity 1s ease-in-out;
            opacity: 0.5;
        }

        #hidden{
            display: block;
        }
    }
}


</style>