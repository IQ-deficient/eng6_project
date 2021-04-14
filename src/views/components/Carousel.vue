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
                    <p class="lead text-white mt-3">
                        Montenegro is a Balkan country with rugged mountains,
                        medieval villages and a narrow strip of beaches along
                        its Adriatic coastline. The Bay of Kotor, resembling a
                        fjord, is dotted with coastal churches and fortified
                        towns such as Kotor and Herceg Novi. Durmitor National
                        Park, home to bears and wolves, encompasses limestone
                        peaks, glacial lakes and 1,300m-deep Tara River Canyon.
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
