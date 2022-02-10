<template>
    <div class="review-container container-fluid mt-5">
        <div class="container pt-5">
            
            <!-- ROW -->
            <div class="row d-flex justify-content-center text-center container-info pt-5">
                
                <!-- TESTIMONIAL IMG -->
                <img class="testimonial" style="width: 8rem" src="../assets/img/man_testimonial.png" alt="">
                <!-- / TESTIMONIAL IMG -->

                <!-- TEXT AND AUTHOR -->
                <p class="fst-italic mt-4"> Integer eget hendrerit nisl. Maecenas in turpis imperdiet turpis rutrum convallis non eu nisi. Integer interdum gravida lacus efficitur tempus. Praesent elit odio, scelerisque id justo eget, luctus pretium ipsum. Proin justo est, convallis nec eleifend consectetur, blandit id dui. Fusce at diam vel turpis sagittis lobortis. </p>
                <p><span class="fw-bold">Darìo Pineda</span>, Theme Fusion</p>
                <!-- / TEXT AND AUTHOR -->
            
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

.review-container{
    background-image: $testimonial-img;
    height: 500px;
    background-size: contain;
    background-position: center;
    background-repeat: repeat;
    color: $white-color;
}

</style>