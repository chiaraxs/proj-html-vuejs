<template>
    <div class="review-container container-fluid mt-5">
        <div class="container pt-5">
            
            <div class="row d-flex justify-content-center text-center container-info pt-5">
                <img class="testimonial" style="width: 8rem" src="../assets/img/man_testimonial.png" alt="">
                <p class="fst-italic mt-4"> Integer eget hendrerit nisl. Maecenas in turpis imperdiet turpis rutrum convallis non eu nisi. Integer interdum gravida lacus efficitur tempus. Praesent elit odio, scelerisque id justo eget, luctus pretium ipsum. Proin justo est, convallis nec eleifend consectetur, blandit id dui. Fusce at diam vel turpis sagittis lobortis. </p>
                <p><span class="fw-bold">Darìo Pineda</span>, Theme Fusion</p>
               
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

.review-container{
    background-image: url(../assets/img/testimonials_home_1_bg.jpg);
    height: 500px;
    background-size: contain;
    background-position: center;
    background-repeat: repeat;
    color: $white-color;
}

</style>