<template>
    <section class="section he-ln">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-12">
                    <div class="section__header--secondary">
                        <div class="row align-items-center items-gap">
                            <div class="col-12 col-lg-8">
                                <h2 class="h1 wow fadeInUp" data-wow-duration="600ms">
                                    Latest News
                                </h2>
                            </div>
                            <div class="col-12 col-lg-4">
                                <div class="h-e-pagination justify-content-start justify-content-lg-end">
                                    <button aria-label="previous slide" class="slide-btn prev-h-n-case">
                                        <i class="tech-left-angle"></i>
                                    </button>
                                    <button aria-label="next slide" class="slide-btn next-h-n-case">
                                        <i class="tech-right-angle"></i>
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row items-gap">
                <div class="col-12">
                    <div class="he-ln___slider">
                        <div class="swiper-wrapper">
                            <div class="he-ln__single swiper-slide">
                                <span class="tg">
                                    News
                                </span>
                                <div class="thumb">
                                    <router-link to="/blog-details">
                                        <img :src="require('@/assets/images/home-eight/seven.png')" alt="Image">
                                    </router-link>
                                </div>
                                <div class="content">
                                    <h4>
                                        <router-link to="/blog-details">ZOBOX-LLM V.1 is released in Beta version. Coming soon 🚀</router-link>
                                    </h4>
                                    <p>
                                        <span>02</span>
                                        July 2022
                                    </p>
                                </div>
                            </div>
                            <div class="he-ln__single swiper-slide">
                                <span class="tg">
                                    News
                                </span>
                                <div class="thumb">
                                    <router-link to="/blog-details">
                                        <img :src="require('@/assets/images/home-eight/five.png')" alt="Image">
                                    </router-link>
                                </div>
                                <div class="content">
                                    <h4>
                                        <router-link to="/blog-details">The first tool integrated into the workspace (Media Edit Tool) ✅</router-link>
                                    </h4>
                                    <p>
                                        <span>02</span>
                                        July 2022
                                    </p>
                                </div>
                            </div>
                            
                            <div class="he-ln__single swiper-slide">
                                <span class="tg">
                                    News
                                </span>
                                <h4>
                                    <router-link to="/blog-details">Turkey's Big Language Model was announced with T3 AI'LE 🚀</router-link>
                                </h4>
                                <div class="thumb">
                                    <router-link to="/blog-details">
                                        <img :src="require('@/assets/images/home-eight/six.png')" alt="Image">
                                    </router-link>
                                </div>
                                <div class="content">
                                    <p>
                                        <span>24</span>
                                        Feb 2024
                                    </p>
                                </div>
                            </div>
                            <div class="he-ln__single swiper-slide">
                                <span class="tg">
                                    News
                                </span>
                                <h4>
                                    <router-link to="/blog-details">OpenAI introduces GPT-4o, the new version of ChatGPT 🤖</router-link>
                                </h4>
                                <div class="thumb">
                                    <router-link to="/blog-details">
                                        <img :src="require('@/assets/images/home-eight/ten.png')" alt="Image">
                                    </router-link>
                                </div>
                                <div class="content">
                                    <p>
                                        <span>14</span>
                                        May 2024
                                    </p>
                                </div>
                            </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
    </section>
</template>

<script>
    import Swiper from 'swiper';
    import 'swiper/swiper-bundle.css';

    export default {
        name: "News",
        mounted() {
            new Swiper('.he-ln___slider', {
                slidesPerView: 3,
                spaceBetween: 30,
                loop: true,
                speed: 1000,
                autoplay: {
                    delay: 4000,
                },
                navigation: {
                    nextEl: '.next-h-n-case',
                    prevEl: '.prev-h-n-case',
                },
            });
        }
    }
</script>

<style>
    .he-ln___slider {
        overflow: hidden;
    }
</style>