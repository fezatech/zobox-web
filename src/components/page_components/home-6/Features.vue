<template>
    <section class="section case-sec pb-0">
        <div class="bg-im section__header--secondary">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-12">
                        <div class="section__header--secondary m-0 p-0">
                            <div class="row align-items-center items-gap">
                                <div class="col-12 col-lg-8">
                                    <h2 class="h2 wow fadeInUp" data-wow-duration="600ms">
                                        Our Awesome
                                        <span>Features</span>
                                    </h2>
                                </div>
                                <div class="col-12 col-lg-4">
                                    <div class="case-pagination cmn-pagination"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="case__slider">
                        <div class="swiper-wrapper">
                            <div class="case__slider-single swiper-slide">
                                <span>
                                    Features - 01
                                </span>
                                <div class="content">
                                    <h4 class="h4">Code Master</h4>
                                    <p>
                                        Developing software is now much easier with the software language you need and a language model specifically trained for the field.
                                    </p>
                                    <div class="section__content-cta">
                                        <router-link to="/use-case-details">
                                            Learn More
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                            <div class="case__slider-single swiper-slide">
                                <span>
                                    Features - 02
                                </span>
                                <div class="content">
                                    <h4 class="h4">Screenshot to Code</h4>
                                    <p>
                                        Now you can create seamless UI designs with just a screenshot and save a lot of time. Just take a screenshot and send it to the application. 
                                    </p>
                                    <div class="section__content-cta">
                                        <router-link to="/use-case-details">
                                            Learn More
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                            <div class="case__slider-single swiper-slide">
                                <span>
                                    Features - 03
                                </span>
                                <div class="content">
                                    <h4 class="h4">Super Search</h4>
                                    <p>
                                        Have you ever imagined being able to ask for information, advice, and ideas, all
                                        enriched by generated code?
                                    </p>
                                    <div class="section__content-cta">
                                        <router-link to="/use-case-details">
                                            Learn More
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                            <div class="case__slider-single swiper-slide">
                                <span>
                                    Features - 04
                                </span>
                                <div class="content">
                                    <h4 class="h4">Clean Code and Debugging</h4>
                                    <p>
                                        Use ZOBOX Code Master for more understandable and efficient codes! In this way, you can work much more comfortably as a team.
                                    </p>
                                    <div class="section__content-cta">
                                        <router-link to="/use-case-details">
                                            Learn More
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                            <div class="case__slider-single swiper-slide">
                                <span>
                                    Features - 05
                                </span>
                                <div class="content">
                                    <h4 class="h4">Code Quality Analysis</h4>
                                    <p>
                                        ZOBOX Code Master analyzes code quality and helps developers identify potential bugs and code quality improvements.
                                    </p>
                                    <div class="section__content-cta">
                                        <router-link to="/use-case-details">
                                            Learn More
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script scoped>
    import Swiper from 'swiper';
    import 'swiper/swiper-bundle.css';

    export default {
        name: "Features",
        mounted() {
            new Swiper('.case__slider', {
                slidesPerView: 'auto',
                slidesPerGroup: 2,
                spaceBetween: 30,
                loop: true,
                speed: 1000,
                pagination: {
                    el: '.case-pagination',
                    clickable: true,
                },
                autoplay: {
                    delay: 4000,
                },
            });
        },
    }
</script>

<style scoped>
    .case__slider {
        overflow: hidden;
    }
</style>

<style>
    .home-six-dark .bg-im {
        background-image: url('~@/assets/images/home-six/header-bg.png');
    }

    .bg-im {
        background-image: url('~@/assets/images/home-six/header-bg-light.png');
    }

    .home-six .case-pagination.cmn-pagination .swiper-pagination-bullet {
        width: 16px;
        height: 6px;
        background-color: #626262;
        border-radius: 100px;
        border: 0px !important;
    }

    .home-six .case-pagination.cmn-pagination .swiper-pagination-bullet::before {
        background-color: transparent;
    }

    .home-six.home-six-dark .case-pagination.cmn-pagination .swiper-pagination-bullet-active {
        width: 38px;
        background-color: #e6f85e;
    }

    .home-six .case-pagination.cmn-pagination .swiper-pagination-bullet-active {
        width: 38px;
        background-color: #181818;
    }
</style>