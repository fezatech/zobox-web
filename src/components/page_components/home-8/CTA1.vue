<template>
    <section class="section h-e-cta bg-img">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-12 col-lg-10">
                    <div class="h-e-cta__inner text-center wow fadeInUp" data-wow-duration="600ms"
                        data-wow-delay="300ms">
                        <router-link to="/" class="logo">
                            <img :src="require('@/assets/images/home-four/logo.png')" alt="Image">
                        </router-link>
                        <h2 class="h1 fw-5">Breakthrough in Your Journey in the World of AI</h2>
                        <div class="section__content-cta">
                            <router-link to="/about" class="btn btn-fo">Explore Workspace</router-link>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "CTA1",
    }
</script>

<style>
    .h-e-cta.bg-img {
        background-image: url('~@/assets/images/home-eight/cta-bg.png');
    }
</style>