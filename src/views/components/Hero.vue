<template>
    <section class="section-hero section-shaped my-0">
        <div class="shape shape-style-1 shape-primary">
            <!-- <span class="span-150"></span>
            <span class="span-50"></span>
            <span class="span-50"></span>
            <span class="span-75"></span>
            <span class="span-100"></span>
            <span class="span-75"></span>
            <span class="span-50"></span>
            <span class="span-100"></span>
            <span class="span-50"></span>
            <span class="span-100"></span> -->
            <img src="img/brand/DyaiXx.jpg" alt="MNE" class="img-fluid" />
        </div>
        <div class="container shape-container d-flex align-items-center">
            <div class="col px-0">
                <div class="row justify-content-center align-items-center">
                    <div class="col-lg-7 text-center pt-lg">
                        <p
                            class="lead text-dark mt-4 mb-5"
                            style="font-size: 20px"
                        >
                            Bursting at the seams with majestic mountains,
                            breathtaking beaches and larger-than-life locals,
                            minuscule Montenegro proves once and for all that
                            good things do indeed come in small packages.
                        </p>
                        <img
                            src="img/brand/Coat_of_arms_of_Montenegro.svg.png"
                            style="width: 250px"
                            class="img-fluid mb-5 zoom"
                        />

                        <!-- <div class="btn-wrapper">
                            <base-button tag="a"
                                         href="https://demos.creative-tim.com/vue-argon-design-system/documentation"
                                         class="mb-3 mb-sm-0"
                                         type="info"
                                         icon="fa fa-code">
                                Components
                            </base-button>
                            <base-button tag="a"
                                         href="https://www.creative-tim.com/product/vue-argon-design-system"
                                         class="mb-3 mb-sm-0"
                                         type="white"
                                         icon="ni ni-cloud-download-95">
                                Download Vue
                            </base-button>
                        </div> -->
                    </div>
                </div>
                <div
                    class="row align-items-center justify-content-around stars-and-coded"
                >
                    <div class="col-sm-4">
                        <!-- <span class="text-white alpha-7 ml-3">Star us on</span> -->
                        <!-- <a href="https://github.com/creativetimofficial/argon-design-system" target="_blank" title="Support us on Github">
                            <img src="img/brand/github-white-slim.png" style="height: 22px; margin-top: -3px">
                        </a> -->
                    </div>
                    <div class="col-sm-4 mt-4 mt-sm-0 text-right">
                        <!-- <span class="text-white alpha-7">Coded by</span> -->
                        <!-- <a href="https://www.creative-tim.com" target="_blank" title="Creative Tim - Premium Bootstrap Themes and Templates">
                            <img src="img/brand/creativetim-white-slim.png" class="ml-3" style="height: 30px;">
                        </a> -->
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {};
</script>
<style>
.zoom {
    /* padding: 50px; */
    /* background-color: green; */
    transition: transform 0.2s; /* Animation */
    /* width: 200px; */
    /* height: 200px; */
    /* margin: 0 auto; */
}

.zoom:hover {
    transform: scale(
        1.3
    ); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
}
</style>
