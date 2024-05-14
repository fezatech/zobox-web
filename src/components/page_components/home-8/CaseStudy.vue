<template>
    <section class="section h-case-study">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-12 col-lg-6">
                    <div class="section__header wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <h2 class="h1">Case Study</h2>
                    </div>
                </div>
            </div>
            <div class="row items-gap">
                <div class="col-12 col-lg-6">
                    <div class="h-case-study__single alt-er wow fadeInUp" data-wow-duration="600ms"
                        data-wow-delay="300ms">
                        <div class="thumb">
                            <router-link to="use-case-details" class="ig">
                                <img :src="require('@/assets/images/home-eight/one.png')" alt="Image">
                            </router-link>
                            <router-link to="use-case-details" class="ic">
                                <i class="fa-solid fa-arrow-up-long"></i>
                            </router-link>
                        </div>
                        <div class="content">
                            <span>Peronel IVR System</span>
                            <h4>
                                <router-link to="use-case-details">Get an artificial intelligence assistant to support you in your daily life plans and business processes.</router-link>
                            </h4>
                        </div>
                    </div>
                    <div class="h-case-study__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <div class="thumb">
                            <router-link to="use-case-details" class="ig">
                                <img :src="require('@/assets/images/home-eight/two.png')" alt="Image">
                            </router-link>
                            <router-link to="use-case-details" class="ic">
                                <i class="fa-solid fa-arrow-up-long"></i>
                            </router-link>
                        </div>
                        <div class="content">
                            <span>Code Assistant</span>
                            <h4>
                                <router-link to="use-case-details">It is now very easy to develop software with specialized artificial intelligence models.</router-link>
                            </h4>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-lg-6">
                    <div class="h-case-study__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <div class="thumb">
                            <router-link to="use-case-details" class="ig">
                                <img :src="require('@/assets/images/home-eight/four.png')" alt="Image">
                            </router-link>
                            <router-link to="use-case-details" class="ic">
                                <i class="fa-solid fa-arrow-up-long"></i>
                            </router-link>
                        </div>
                        <div class="content">
                            <span>ZOBOX-LLM</span>
                            <h4>
                                <router-link to="use-case-details">Through the support of ZOBOX-LLM, all your business processes and daily life will become much easier.</router-link>
                            </h4>
                        </div>
                    </div>
                    <div class="h-case-study__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <div class="thumb">
                            <router-link to="use-case-details" class="ig">
                                <img :src="require('@/assets/images/home-eight/three.png')" alt="Image">
                            </router-link>
                            <router-link to="use-case-details" class="ic">
                                <i class="fa-solid fa-arrow-up-long"></i>
                            </router-link>
                        </div>
                        <div class="content">
                            <span>Visual Tools</span>
                            <h4>
                                <router-link to="use-case-details">Create a single prompt visual and use it in your presentation or resume with feedback from ZOBOX-LLM.</router-link>
                            </h4>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "CaseStudy",
    }
</script>