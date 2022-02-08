<template>
   
    <!-- CONTAINER HEADER-BOX -->
    <div>

        <!-- PRE HEADHER - COMPONENTE A PARTE? -->
        <div></div>
        <!-- / PRE HEADHER -->
        
        <!-- NAVBAR -->
        <nav class="navbar container-fluid navbar-light bg-light d-flex justify-content-around align-items-center">

            <!-- LOGO -->
            <div class="logo-container py-2">
                <img src="@/assets/img/classic_shop_logo1x.png" alt="logo" >
            </div>
            <!-- / LOGO -->
                
            <!-- CONTAINER MENU E BUTTON -->
            <div class="container-menu d-flex ">
                   
                <!-- MENU LIST -->
                <ul class="d-flex list-unstyled">
                    <li class="px-3" v-for="item in navbar" :key="item.id">
                        <a class="text-secondary text-decoration-none" :href="item.url"> {{item.label}} </a> 
                        <i class="fas fa-chevron-down"></i>
                    </li>
                </ul>
                <!-- / MENU LIST -->
                    
                 <!-- BUTTON -->
                <button type="button" class="btn text-light text-uppercase rounded-pill me-3 mt">Shop now!</button>
                <!-- / BUTTON -->

                <!-- SEARCH LENS -->
                <a href="#"><i class="fas fa-search mt-1"></i></a>
                <!-- / SEARCH LENS -->
                    
            </div>
            <!-- / CONTAINER MENU E BUTTON -->
            
                
           
        </nav>
        <!-- / NAVBAR -->
    </div>
   <!-- / CONTAINER HEADER-BOX -->


</template>


<script>
export default {
    props: {
       navbar: Array,
    },
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

a{
    color: gray;
}
.fa-chevron-down{
    font-size: 10px;
}

.fa-search{
    font-size: 20px;
}

button{
    background-color: $button-color;
}

</style>