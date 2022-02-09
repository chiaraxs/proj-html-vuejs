<template>
    <div class="container-fluid final-container">
        <div class="container">
            <div class="row">

                <p class="text-light text-center mt-5">
                    &copy; Copyright 2021 - 2022 | Avada Theme by Chiara | All Rights Reserved | Powered by Boolean
                </p>

                <div class="icon d-flex justify-content-center mt-2 pb-5">

                    <!-- VISA -->
                    <img class="px-2" src="https://img.icons8.com/color-glass/48/000000/visa.png"/>

                    <!-- PAYPAL -->
                    <img class="px-2" src="https://img.icons8.com/color/48/000000/paypal.png"/>

                    <!-- MASTERCARD -->
                    <img class="px-2" src="https://img.icons8.com/fluency/48/000000/mastercard.png"/>

                    <!-- DISCOVER -->
                    <img class="px-2" src="https://img.icons8.com/fluency/48/000000/discover.png"/>

                    <!-- AMAZON -->
                    <img class="px-2" src="https://img.icons8.com/color/48/000000/amazon.png"/>
            
                </div>

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

.final-container{
    background-color: #1D1F22;

    .icon{
        img{
            width: 60px;
        }
    }
}

</style>