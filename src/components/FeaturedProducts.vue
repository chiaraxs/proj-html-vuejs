<template>
    <div class="container-fluid">
        <div class="container mt-5">
            
            <div class="text-center">
                <h1>Featured Products</h1>
                <p>Must have products from our top sellers</p>
            </div>
                    
                
            <!-- BUTTONS -->
            <div class="mt-4 justify-content-center d-flex">
                    
                <button type="button" class="btn btn-light border border-secondary px-5 fw-bold">Men</button>
                <button type="button" class="btn btn-light border border-secondary px-5  fw-bold">Women</button>
                <button type="button" class="btn btn-light border border-secondary px-5  fw-bold">Accessories</button>
                
            </div>  
             <!-- / BUTTONS -->
                    
            <!-- OUTFITS CONTAINER -->
            <div class="row mt-5">

                <!-- OUTFIT 1 -->
                <div class="col">
                            
                    <img src="../assets/img/black_elegant_leather_jacket-200x260.jpg" alt="">
                    <p class="fw-bold">Black Leather Jacket</p>
                    <p>Men, Jacktes, Jeans</p>
                    <span class="text-decoration-line-through">$235</span> <span>$200</span>
                        
                </div>
                <!-- / OUTFIT 1  -->

                <!-- OUTFIT 2 -->
                <div class="col">
                                
                    <img src="../assets/img/black_leather_suit-200x260.jpg" alt="">
                    <p class="fw-bold">Black Leather Suit</p>
                    <p>Men, Jacktes</p>
                    <span>$176</span>
                        
                </div>
                <!-- / OUTFIT 2 -->
                        
                <!-- OUTFIT 3 -->
                <div class="col">
                    <img src="../assets/img/blue_jacket_and_white_stripe_tee-200x260.jpg" alt="">
                    <p class="fw-bold">Blue Jacket & Stripe Tee</p>
                    <p>Men, Jacktes, Suits</p>
                    <span>$580</span>
                </div>
                <!-- / OUTFIT 3 -->
                            
                <!-- OUTFIT 4 -->
                <div class="col">
                    <img src="../assets/img/modern_black_leather_suit-200x260.jpg" alt="">
                    <p class="fw-bold">Modern Black Leather Suit</p>
                    <p>Men, Jacktes</p>
                    <span>$96</span>
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