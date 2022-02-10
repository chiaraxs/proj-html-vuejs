<template>
    <div class="container-fluid mt-5">
        <div class="row text-center text-light">

            <!-- WINTER COLLECTION -->
            <div class="col-4 winter-collection ">
                
                <div class="details">
                    <h2>Winter Collection</h2>
                    <p class="text-uppercase">stilysh and warm</p>
                    <button type="button" class="btn text-light text-uppercase rounded-pill border border-white">view more</button>
                </div>
                
            </div>
            <!-- / WINTER COLLECTION -->

            <!-- SPRING COLLECTION -->
            <div class="col-4 spring-collection">
                
                <div class="details">
                    <h2>Spring Collection</h2>
                    <p class="text-uppercase">bright and colorful</p>
                    <button type="button" class="btn text-light text-uppercase rounded-pill border border-white mb-4">view more</button>
                </div>
                
            </div>
            <!-- / SPRING COLLECTION -->

            <!-- AUTUMN COLLECTION -->
            <div class="col-4 autumn-collection">
                
                <div class="details">
                    <h2>Autumn Collection</h2>
                    <p class="text-uppercase">rich and comfortable</p>
                    <button type="button" class="btn text-light text-uppercase rounded-pill border border-white">view more</button>
                </div>
            
            </div>
            <!-- / AUTUMN COLLECTION -->
            
        </div>

    </div>
</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.winter-collection {
    background-image: $winter-collection;
    background-size: cover;
    background-position: center top;
}

.spring-collection{
    background-image: $spring-collection;
    background-size: cover;
    background-position: center top;
}

.autumn-collection{
    background-image: $autumn-collection;
    background-size: cover;
    background-position: center top;
}

.details{
    margin-top: 300px;
}
</style>