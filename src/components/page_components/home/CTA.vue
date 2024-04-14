<template>
    <section class="section cta bg-img ctaa mt-7" style="margin: 5% auto;">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-12 col-xl-6">
                    <div class="section__header m-0 text-center wow fadeInUp" data-wow-duration="600ms"
                        data-wow-delay="300ms">
                        <h2 class="h2">
                            Start creating your account and use your AI workspace
                        </h2>
                        <div class="form-cta">
                            <router-link to="/contact-us" class="btn btn--quinary">
                                create account and try free AI tools
                            </router-link>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "CTA",
}
</script>

<style scoped>
.cta {
    background-image: url('~@/assets/images/cta-bg.png');
}
</style>