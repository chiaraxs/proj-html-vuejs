<template>
    
    <!-- CONTAINER HERO -->
    <div class="hero container-fluid mt-4">
        
        <div class="container">
           
           <!-- TEXT CONTAINER CENTER -->
            <div class="row text-center container-info">
                
                <h1>Brand New Arrivals</h1>
                <p class="text-uppercase">new collection from new york</p>

                <!-- BUTTONS -->
                <div class="button py-3">
                   
                    <button type="button" class="btn text-light text-uppercase rounded-pill border border-white mx-3">view all</button>
                    <button type="button" class="btn text-light text-uppercase rounded-pill border border-white">lookbook</button>
                
                </div>
                <!-- /BUTTONS -->
                
            </div>
            <!-- TEXT CONTAINER CENTER-->
        </div>

    </div>
    <!-- / CONTAINER HERO -->


</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.hero{
    background-image: $bg-hero;
    height: 500px;
    background-size: cover;
    background-position: bottom bottom;
    color: $white-color;
    

    .container-info{
        padding-top: 150px;

        h1{
            font-size: 80px;
        }

        p{
            font-size: 20px;
        }

       button{
            &:hover{
                background-color: $shocking-color;
            }
        } 
    }
}

</style>