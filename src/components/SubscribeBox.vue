<template>
    <div class="container-fluid subscribe-container">
        <div class="container container-box d-flex justify-content-center">
            <div class="row">

                <!-- title -->
                <div class="col-6 d-flex">
                    <div class="icon rounded-circle text-center me-4">
                        <i class="fa-regular fa-envelope mt-3"></i>
                    </div>

                    <div class="text text-light mt-3">
                        <h5>Subscribe now and get special offers</h5>
                    </div>
                </div>
                <!-- / title -->

                <!-- input -->
                <div class="col-6 d-flex">
                    <div class="input-group input">
                        
                        <input type="text" class="form-control rounded-pill" placeholder="Insert your email" aria-label="Username">
                    </div>

                    <!-- button -->
                    <button type="button" class="btn btn-primary text-uppercase rounded-pill px-3 ms-3">send</button>
                    <!--  / button -->
                    
                </div>
                <!-- / input -->
            </div>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';


.subscribe-container{
    height: 200px;
    background-color: $deep-gray-bg;

   


    .icon{
        width: 50px;
        height: 50px;
        background-color: $darks-late-gray-bg;

        &:hover{
            background-color: $shocking-color;
        }

        .fa-regular{
            font-size: 20px;
            color: $edward-color;
        }
    }

    .input{
        width: 450px;
    }

}

.container-box{
   padding-top: 70px;
}

button{
    width: 150px;

    &:hover{
        background-color: $shocking-color;
    }
}
</style>