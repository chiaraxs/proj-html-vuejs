<template>
    
    <div class="container-fluid container-shipping mt-5">
        <div class="container d-flex justify-content-center">
            <div class="row mt-3">
            
                <div class="text-center mb-4">
                    
                    <div class="d-flex justify-content-center align-items-center">
                        <div class="border_bottom me-5"></div>
                        <h1>From Our Blog</h1>
                        <div class="border_bottom ms-5"></div>
                    </div>


                    <p class="text-muted">The latest Classic Shop news</p>
                </div>

                <!-- BOX 1 -->
                <div class="col-4">
                    <div class="box">
                        <div>
                            <img src="../assets/img/post_img_12-320x202.jpg" alt="">
                        </div>
                        <span class="fw-bold">Aenean lobortis sapien enim viverra</span>
                        <br>
                        <span class="text-muted">September 9th, 2015 | 0 comments</span>
                        <br>
                        <span class="text-muted">Etiam finibus suscipit odio, quis cursus dui pharetra vitae. Donec hendrerit tincidunt congue.</span>
                    </div>
                </div>
                <!-- / BOX 1 -->

                <!-- BOX 2 -->
                <div class="col-4 ">
                    <div class="box">
                        <div>
                            <img src="../assets/img/post_img_11-320x202.jpg" alt="">
                        </div>
                        <span class="fw-bold">Duic ac massa semper maximus</span>
                        <br>
                        <span class="text-muted">September 9th, 2015 | 0 comments</span>
                        <br>
                        <span class="text-muted">Etiam finibus suscipit odio, quis cursus dui pharetra vitae. Donec hendrerit tincidunt congue.</span>
                    </div>
                </div>
                <!-- / BOX 2 -->

                <!-- BOX 3 -->
                <div class="col-4 ">
                    <div class="box">
                        <div>
                            <img src="../assets/img/post_img_10-320x202.jpg" alt="">
                        </div>
                        <span class="fw-bold">Nunc femrint nulla eu justo sem id</span>
                        <br>
                        <span class="text-muted">September 9th, 2015 | 0 comments</span>
                        <br>
                        <span class="text-muted">Etiam finibus suscipit odio, quis cursus dui pharetra vitae. Donec hendrerit tincidunt congue.</span>
                    </div>
                </div>
                
                <!-- / BOX 3 -->
            </div>
        </div>
        
        <hr class="mx-5 mt-5">
    
    </div>
    
</template>


<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

.border_bottom{
    border-bottom: 1px solid $edward-color;
    width: 400px;
}
.box{
    width: 300px;
    line-height: 30px;
}

</style>