<template>
    <footer class="footer has-cards">
        <div class="container container-lg">
            <div class="row justify-content-center text-center mb-lg-3">
                <div class="col-lg-8">
                    <h2 class="display-3">More about Montenegro</h2>
                </div>
            </div>
            <div class="row">
                <div class="col-md-4 mb-5 mb-md-0">
                    <div class="card card-lift--hover shadow border-0">
                        <div class="centered" style="color: white">South</div>
                        <router-link to="/south" title="Coast of Montenegro">
                            <img
                                v-lazy="'img/theme/south.jpg'"
                                class="card-img"
                            />
                        </router-link>
                    </div>
                </div>
                <div class="col-md-4 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <div class="centered" style="color: white">Center</div>
                        <router-link to="/center" title="Central Region">
                            <img
                                v-lazy="'img/theme/center.jpg'"
                                class="card-img"
                            />
                        </router-link>
                    </div>
                </div>
                <div class="col-md-4 mb-5 mb-lg-0">
                    <div class="card card-lift--hover shadow border-0">
                        <div class="centered" style="color: white">North</div>
                        <router-link to="/north" title="Northern Part">
                            <img
                                v-lazy="'img/theme/north.jpg'"
                                class="card-img"
                            />
                        </router-link>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <!-- <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h3 class="text-primary font-weight-light mb-2">
                        Thank you for supporting us!
                    </h3>
                    <h4 class="mb-0 font-weight-light">
                        Let's get in touch on any of these platforms.
                    </h4>
                </div>
                <div class="col-lg-6 text-lg-center btn-wrapper">
                    <a
                        target="_blank"
                        rel="noopener"
                        href="https://twitter.com/creativetim"
                        class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg"
                        data-toggle="tooltip"
                        data-original-title="Follow us"
                    >
                        <i class="fa fa-twitter"></i>
                    </a>
                    <a
                        target="_blank"
                        rel="noopener"
                        href="https://www.facebook.com/creativetim"
                        class="btn btn-neutral btn-icon-only btn-facebook btn-round btn-lg"
                        data-toggle="tooltip"
                        data-original-title="Like us"
                    >
                        <i class="fa fa-facebook-square"></i>
                    </a>
                    <a
                        target="_blank"
                        rel="noopener"
                        href="https://dribbble.com/creativetim"
                        class="btn btn-neutral btn-icon-only btn-dribbble btn-lg btn-round"
                        data-toggle="tooltip"
                        data-original-title="Follow us"
                    >
                        <i class="fa fa-dribbble"></i>
                    </a>
                    <a
                        target="_blank"
                        rel="noopener"
                        href="https://github.com/creativetimofficial"
                        class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg"
                        data-toggle="tooltip"
                        data-original-title="Star on Github"
                    >
                        <i class="fa fa-github"></i>
                    </a>
                </div>
            </div> -->
            <hr/>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{ year }} Group 5 - English Language 6 -
                        Mediterranean University FIT
                        <!-- <a
                            href="https://www.creative-tim.com"
                            target="_blank"
                            rel="noopener"
                            >Creative Tim</a
                        >
                        &
                        <a
                            href="https://www.binarcode.com"
                            target="_blank"
                            rel="noopener"
                            >Binar Code</a
                        > -->
                    </div>
                </div>
                <div class="col-md-6">
                    <!-- <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <a
                                href="https://www.creative-tim.com"
                                class="nav-link"
                                target="_blank"
                                rel="noopener"
                                >Creative Tim</a
                            >
                        </li>
                        <li class="nav-item">
                            <a
                                href="https://www.creative-tim.com/presentation"
                                class="nav-link"
                                target="_blank"
                                rel="noopener"
                                >About Us</a
                            >
                        </li>
                        <li class="nav-item">
                            <a
                                href="http://blog.creative-tim.com"
                                class="nav-link"
                                target="_blank"
                                rel="noopener"
                                >Blog</a
                            >
                        </li>
                        <li class="nav-item">
                            <a
                                href="https://github.com/creativetimofficial/argon-design-system/blob/master/LICENSE.md"
                                class="nav-link"
                                target="_blank"
                                rel="noopener"
                                >MIT License</a
                            >
                        </li>
                    </ul> -->
                    <ul class="nav nav-footer justify-content-end">
                        <!-- navbar-nav align-items-lg-center ml-lg-auto -->
                        <li class="nav-item">
                            <a
                                class="nav-link nav-link-icon"
                                href="mailto:gazivodavladimir@gmail.com"
                                target="_blank"
                                rel="noopener"
                                data-toggle="tooltip"
                                title="Gmail"
                            >
                                <i class="fa fa-google"></i>
                                <!-- <span class="nav-link-inner--text d-lg-none"
                                    >Gmail</span
                                > -->
                            </a>
                        </li>
                        <li class="nav-item">
                            <a
                                class="nav-link nav-link-icon"
                                href="https://github.com/IQ-deficient"
                                target="_blank"
                                rel="noopener"
                                data-toggle="tooltip"
                                title="Github"
                            >
                                <i class="fa fa-github"></i>
                                <!-- <span class="nav-link-inner--text d-lg-none"
                                    >Github</span
                                > -->
                            </a>
                        </li>
                        <li class="nav-item">
                            <a
                                class="nav-link nav-link-icon"
                                href="https://www.instagram.com/gruesome_v/"
                                target="_blank"
                                rel="noopener"
                                data-toggle="tooltip"
                                title="Instagram"
                            >
                                <i class="fa fa-instagram"></i>
                                <!-- <span class="nav-link-inner--text d-lg-none"
                                    >Instagram</span
                                > -->
                            </a>
                        </li>
                        <li class="nav-item">
                            <a
                                class="nav-link nav-link-icon"
                                href="img/theme/chad.png"
                                target="_blank"
                                rel="noopener"
                                data-toggle="tooltip"
                                title="Easter egg"
                            >
                                <i class="fa fa-image"></i>
                                <!-- <span class="nav-link-inner--text d-lg-none"
                                    >Instagram</span
                                > -->
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
    name: "app-footer",
    data() {
        return {
            year: new Date().getFullYear(),
        };
    },
};
</script>
<style>
.centered {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>
