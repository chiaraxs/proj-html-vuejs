<template>
    <div class="container-fluid">
        <div class="container mt-5">
            
            <div class="text-center">
                <h1>Featured Products</h1>
                <p class="text-muted">Must have products from our top sellers</p>
            </div>
                    
                
            <!-- BUTTONS -->
            <div class="mt-4 justify-content-center d-flex">
                    
                <button type="button" class="btn btn-light border border-secondary px-5 fw-bold">Men</button>
                <button type="button" class="btn btn-light border border-secondary px-5 fw-bold">Women</button>
                <button type="button" class="btn btn-light border border-secondary px-5 fw-bold">Accessories</button>
                
            </div>  
             <!-- / BUTTONS -->
                    
            <!-- OUTFITS CONTAINER -->
            <div class="row mt-5">

                <!-- OUTFIT 1 -->
                <div class="col-3">
                    
                    <div class="container-outfit">
                        <img src="../assets/img/black_elegant_leather_jacket-400x520.jpg" alt="">
                        <span class="fw-bold">Black Leather Jacket</span>
                        <br>
                        <span class="text-muted">Men, Jacktes, Jeans</span>
                        <br>
                        <span class="text-decoration-line-through text-primary me-2">$235</span> <span class="text-primary">$200</span>
                    </div>
                   
                        
                </div>
                <!-- / OUTFIT 1  -->

                <!-- OUTFIT 2 -->
                <div class="col-3">
                    
                    <div class="container-outfit">
                        <img src="../assets/img/black_leather_suit-400x520.jpg" alt="">
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
                        <img src="../assets/img/blue_jacket_and_white_stripe_tee-400x520.jpg" alt="">
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
                        <img src="../assets/img/modern_black_leather_suit-400x520.jpg" alt="">
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



</style>