<template>
    <div class="container-fluid mt-5">
        <div class="row text-center text-light">

            <!-- WINTER COLLECTION -->
            <div class="col winter-collection ">
                
                <div class="details">
                    <h2>Winter Collection</h2>
                    <p class="text-uppercase">stilysh and warm</p>
                    <button type="button" class="btn text-light text-uppercase rounded-pill border border-white">view more</button>
                </div>
                
            </div>
            <!-- / WINTER COLLECTION -->

            <!-- SPRING COLLECTION -->
            <div class="col spring-collection">
                
                <div class="details">
                    <h2>Spring Collection</h2>
                    <p class="text-uppercase">bright and colorful</p>
                    <button type="button" class="btn text-light text-uppercase rounded-pill border border-white">view more</button>
                </div>
                
            </div>
            <!-- / SPRING COLLECTION -->

            <!-- AUTUMN COLLECTION -->
            <div class="col autumn-collection">
                
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
    width: 500px;
    height: 500px;
    background-image: url("../assets/img/winter_collection_bg.jpg");
    background-size: cover;
    background-position: center top;
}

.spring-collection{
    width: 500px;
    height: 500px;
    background-image: url("../assets/img/spring_collection_bg.jpg");
    background-size: cover;
    background-position: center top;
}

.autumn-collection{
    width: 500px;
    height: 500px;
    background-image: url("../assets/img/autumn_collection_bg.jpg");
    background-size: cover;
    background-position: center top;
}

.details{
    margin-top: 350px;
}
</style>