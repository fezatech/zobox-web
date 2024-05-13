<template>
    <section class="section clone">
        <div class="container">
            <div class="row items-gap align-items-center">
                <div class="col-12 col-lg-6">
                    <div class="clone__thumb wow fadeInUp" data-wow-duration="600ms">
                        <img :src="require('@/assets/images/home-four/art-thumb.png')" alt="Image">
                    </div>
                </div>
                <div class="col-12 col-lg-6">
                    <div class="clone__content section__content">
                        <h2 class="h2 wow fadeInUp">Let artificial intelligence write your resume and cover letter.</h2>
                        <div class="paragraph wow fadeInUp" data-wow-duration="600ms">
                            <p class="text-md">
                                Are you having trouble finding the right words for your resume? Our AI resume builder
                                can find them in no time! It is powered by ZOBOX-LLM, which uses the world's most
                                powerful language models, and can automatically produce texts that are indistinguishable
                                from human authors. <br><br>
                                <a style="font-weight: bolder;">Say goodbye to writer's block. Create the first draft of
                                your resume in seconds.</a>
                            </p>
                        </div>
                        <ul class="wow fadeInUp">
                            <li>
                                Powered by ZOBOX-LLM
                            </li>
                            <li>
                                Generated in seconds
                            </li>
                            <li>
                                Produces human-like text
                            </li>
                            <li>
                                Compatible with corporate culture
                            </li>
                        </ul>
                        <div class="section__content-cta wow fadeInUp" data-wow-duration="600ms">
                            <router-link to="/sign-up" class="btn btn-fo">
                                create My resume
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
    name: "Generate",
}
</script>