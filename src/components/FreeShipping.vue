<template>
    <div class="container-fluid container-shipping mt-5">
        
        <div class="container d-flex justify-content-center">
            
            <!-- ROW -->
            <div class="row mt-5 text-light">
            
                <!-- PROMO BOX SX -->
                <div class="col-6 promo-box me-5">
                    <div class="details ">
                        <h2>70% Off</h2>
                        <p>Vivamus tempor leo lacus, feugiat ut magna aliquam erat.</p>
                        <button type="button" class="btn text-light text-uppercase rounded-pill border border-white mb-4">view more</button>
                    </div>
                </div>
                <!-- / PROMO BOX SX -->

                <!-- FREE SHIPPING DX -->
                <div class="col-6 free-shipping">
                    <div class="details">
                        <h2>Free Shipping</h2>
                        <p>Vivamus tempor leo lacus, feugiat ut magna aliquam erat.</p>
                        <button type="button" class="btn text-light text-uppercase rounded-pill border border-white mb-4">view more</button>
                    </div>
                </div>
                <!-- / FREE SHIPPING DX -->
                
            </div>
            <!-- / ROW -->

        </div>
        
    </div>
</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.container-shipping {
    height: 500px;
    background-image: $confetti-bg;
    background-size: contain;

    .promo-box{
        height: 400px;
        width: 450px;
        background-image: $promo-box-1;
        background-size: cover;
        background-position: bottom;
    }

    .free-shipping{
        height: 400px;
        width: 450px;
        background-image: $promo-box-2;
        background-size: cover;
        background-position: bottom;
    }

    .details{
        width: 250px;
        margin: 200px 0 10px 10px;
        line-height: 30px;
    }
}

button{
   
    &:hover{
        background-color: $shocking-color;
    }
}
</style>