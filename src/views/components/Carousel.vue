<template>
    <section class="section section-lg section-shaped overflow-hidden my-0">
        <div class="shape shape-style-1 shape-default shape-skew">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="container py-0 pb-lg">
            <div class="row justify-content-between align-items-center">
                <div class="col-lg-6 mb-5 mb-lg-0">
                    <h1 class="text-white font-weight-light">Introduction</h1>
                    <p class="lead text-white mt-2">
                        This is a stunning country in Southeast Europe that lies on the shores of the
                      Adriatic Sea. It borders Serbia to the east and northeast, Croatia and Bosnia & Herzegovina
                      to the west and northwest, and Albania to the southeast. Although small in territory,
                      Montenegro is rich in natural beauty and full of contrasts. At a distance of only 100
                      kilometers there are three different natural environments. It's safe to say that
                      Montenegro is at the same time Mediterranean, Adriatic and mountainous.
                    </p>
                    <!-- <a href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                       class="btn btn-white mt-4">See all components</a> -->
                </div>
                <div class="col-lg-6 mb-lg-auto">
                    <div
                        class="rounded shadow-lg overflow-hidden transform-perspective-right"
                    >
                        <b-carousel id="carousel1" controls indicators>
                            <!-- Text slides with image -->
                            <b-carousel-slide
                                img-src="img/theme/xdd.jpg"
                            ></b-carousel-slide>
                            <b-carousel-slide
                                img-src="img/theme/wp2222736-montenegro-wallpapers.jpg"
                            ></b-carousel-slide>
                            <b-carousel-slide
                                img-src="img/theme/wp2222737-montenegro-wallpapers.jpg"
                            ></b-carousel-slide>

                            <b-carousel-slide
                                img-src="img/theme/1403327.jpg"
                            ></b-carousel-slide>
                            
                            <b-carousel-slide
                                img-src="img/theme/1403266.jpg"
                            ></b-carousel-slide>
                            <b-carousel-slide
                                img-src="img/theme/wp2222895-montenegro-wallpapers.jpg"
                            ></b-carousel-slide>
                        </b-carousel>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
    components: {
        BCarousel,
        BCarouselSlide,
    },
};
</script>
<style>
</style>
