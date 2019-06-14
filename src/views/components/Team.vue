<template>
    <section>
        <section class="section section-lg">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">The amazing Team</h2>
                        <p class="lead text-muted">According to the National Oceanic and Atmospheric Administration,
                            Ted, Scambos, NSIDClead scentist, puts the potentially record maximum.</p>
                    </div>
                </div>
                <div class="col-lg-12 team-section">
                    <div class="row">
                        <div class="col-md-5 col-lg-2 mb-4 mb-lg-0">
                            <div class="px-4">
                                <img v-lazy="'img/theme/diego.jpg'"
                                     class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                     style="width: 200px;">
                                <div class="pt-4 text-center">
                                    <h5 class="title">
                                        <span class="d-block mb-1">Diego Waziri</span>
                                        <small class="h6 text-muted">Founder and CEO</small>
                                    </h5>
                                    <div class="mt-3">
                                        <base-button tag="a" href="#" type="warning" icon="fa fa-twitter" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="warning" icon="fa fa-facebook" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="warning" icon="fa fa-dribbble" rounded
                                                     icon-only></base-button>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-5 col-lg-2 mb-4 mb-lg-0">
                            <div class="px-4">
                                <img v-lazy="'img/theme/mohit.jpg'"
                                     class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                     style="width: 200px;">
                                <div class="pt-4 text-center">
                                    <h5 class="title">
                                        <span class="d-block mb-1">Mohit Singh</span>
                                        <small class="h6 text-muted">UI/UX Designer</small>
                                    </h5>
                                    <div class="mt-3">
                                        <base-button tag="a" href="#" type="primary" icon="fa fa-twitter" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="primary" icon="fa fa-facebook" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="primary" icon="fa fa-dribbble" rounded
                                                     icon-only></base-button>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-5 col-lg-2 mb-4 mb-lg-0">
                            <div class="px-4">
                                <img v-lazy="'img/theme/kevin.jpg'"
                                     class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                     style="width: 200px;">
                                <div class="pt-4 text-center">
                                    <h5 class="title">
                                        <span class="d-block mb-1">Kévin Gilibert</span>
                                        <small class="h6 text-muted">Web Developer</small>
                                    </h5>
                                    <div class="mt-3">
                                        <base-button tag="a" href="#" type="info" icon="fa fa-twitter" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="info" icon="fa fa-facebook" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="info" icon="fa fa-dribbble" rounded
                                                     icon-only></base-button>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-5 col-lg-2 mb-4 mb-lg-0">
                            <div class="px-4">
                                <img v-lazy="'img/theme/anton.jpg'"
                                     class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                     style="width: 200px;">
                                <div class="pt-4 text-center">
                                    <h5 class="title">
                                        <span class="d-block mb-1">Anton Bourtnik</span>
                                        <small class="h6 text-muted">Web Developer</small>
                                    </h5>
                                    <div class="mt-3">
                                        <base-button tag="a" href="#" type="success" icon="fa fa-twitter" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="success" icon="fa fa-facebook" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="success" icon="fa fa-dribbble" rounded
                                                     icon-only></base-button>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-md-5 col-lg-2 mb-4 mb-lg-0">
                            <div class="px-4">
                                <img v-lazy="'img/theme/tharshan.jpg'"
                                     class="rounded-circle img-center img-fluid shadow shadow-lg--hover"
                                     style="width: 200px;">
                                <div class="pt-4 text-center">
                                    <h5 class="title">
                                        <span class="d-block mb-1">Tharshan Sivapalan</span>
                                        <small class="h6 text-muted">UI/UX Designer</small>
                                    </h5>
                                    <div class="mt-3">
                                        <base-button tag="a" href="#" type="warning" icon="fa fa-twitter" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="warning" icon="fa fa-facebook" rounded
                                                     icon-only></base-button>
                                        <base-button tag="a" href="#" type="warning" icon="fa fa-dribbble" rounded
                                                     icon-only></base-button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-0">
            <div class="container">
                <card gradient="warning"
                      no-body
                      shadow-size="lg"
                      class="border-0">
                    <div class="p-5 bg-gradient-gold">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">We made website building easier for you.</h3>
                                <p class="lead text-white mt-3">I will be the leader of a company that ends up being
                                    worth billions of dollars, because I got the answers. I understand culture.</p>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href="https://api.lmdfoot.com/"
                                             type="white" block size="lg">
                                    Download Sporty
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>
    </section>
</template>
<script>
</script>
<style>
</style>