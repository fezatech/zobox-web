<template>
    <section class="section tools">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-12 col-xl-6">
                    <div class="section__header wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <h2 class="h2">Other AI Writing Tools</h2>
                    </div>
                </div>
            </div>
            <div class="row items-gap">
                <div class="col-12 col-sm-6 col-lg-3">
                    <div class="tools__single wow fadeInUp" data-wow-duration="600ms">
                        <div class="thumb">
                            <i class="tech-tool-one"></i>
                        </div>
                        <h5 class="h5">
                            <router-link to="/use-case-single">
                                ZOBOX-LLM API
                                <i class="tech-arrow-top">
                                </i>
                            </router-link>
                        </h5>
                    </div>
                </div>
                <div class="col-12 col-sm-6 col-lg-3">
                    <div class="tools__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="200ms">
                        <div class="thumb">
                            <i class="tech-tool-two"></i>
                        </div>
                        <h5 class="h5">
                            <router-link to="/use-case-single">
                                AI Text Generator Tool
                                <i class="tech-arrow-top">
                                </i>
                            </router-link>
                        </h5>
                    </div>
                </div>
                <div class="col-12 col-sm-6 col-lg-3">
                    <div class="tools__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="400ms">
                        <div class="thumb">
                            <i class="tech-tool-three"></i>
                        </div>
                        <h5 class="h5">
                            <router-link to="/use-case-single">
                                Paraphrasing Tool
                                <i class="tech-arrow-top">
                                </i>
                            </router-link>
                        </h5>
                    </div>
                </div>
                <div class="col-12 col-sm-6 col-lg-3">
                    <div class="tools__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="600ms">
                        <div class="thumb">
                            <i class="tech-tool-four"></i>
                        </div>
                        <h5 class="h5">
                            <router-link to="/use-case-single">
                                Text Summarizer
                                <i class="tech-arrow-top">
                                </i>
                            </router-link>
                        </h5>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: "Tools",
    }
</script>