<template>
    <section class="section pb-0 h-e-case">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-12">
                    <div class="section__header--secondary">
                        <div class="row align-items-center items-gap">
                            <div class="col-12 col-lg-8">
                                <h2 class="h1 wow fadeInUp" data-wow-duration="600ms">
                                    WHAT WE DO ?
                                </h2>
                            </div>
                            <div class="col-12 col-lg-4">
                                <div class="h-e-pagination justify-content-start justify-content-lg-end">
                                    <button aria-label="previous slide" class="slide-btn prev-h-e-case">
                                        <i class="tech-left-angle"></i>
                                    </button>
                                    <button aria-label="next slide" class="slide-btn next-h-e-case">
                                        <i class="tech-right-angle"></i>
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="case__slider-h-e">
                        <div class="swiper-wrapper">
                            <div class="case__slider-single-h-e swiper-slide">
                                <div class="content">
                                    <h4 class="h4">ZOBOX-LLM</h4>
                                    <p>
                                        The ZOBOX LLM model is an open-source fine-tuned large language model. It forms
                                        the foundation of ZOBOX's tools.
                                    </p>
                                    <router-link to="/use-case-details">
                                        Learn More
                                    </router-link>
                                </div>
                            </div>
                            <div class="case__slider-single-h-e swiper-slide">
                                <div class="content">
                                    <h4 class="h4">Presentation Maker</h4>
                                    <p>
                                        ZOBOX is a tool that create presentations in minutes thanks to integrated work
                                        of tools such as Image Generator, Media Edit and ZOBOX-LLM.
                                    </p>
                                    <router-link to="/use-case-details">
                                        Learn More
                                    </router-link>
                                </div>
                            </div>
                            <div class="case__slider-single-h-e swiper-slide">
                                <div class="content">
                                    <h4 class="h4">Personel IVR System</h4>
                                    <p>
                                        An AI tool that tracks your daily schedule, makes adjustments, and provides
                                        alerts. It works in integration with different calendar apps.
                                    </p>
                                    <router-link to="/use-case-details">
                                        Learn More
                                    </router-link>
                                </div>
                            </div>
                            <div class="case__slider-single-h-e swiper-slide">
                                <div class="content">
                                    <h4 class="h4">Image Generator</h4>
                                    <p>
                                        Create visuals quickly and
                                        effectively. By enriching ideas, it helps you produce unique and
                                        creative images for your projects.
                                    </p>
                                    <router-link to="/use-case-details">
                                        Learn More
                                    </router-link>
                                </div>
                            </div>
                            <div class="case__slider-single-h-e swiper-slide">
                                <div class="content">
                                    <h4 class="h4">Visual Tools</h4>
                                    <p>
                                        Visual Tools simplifies your tasks by providing visual AI tools in a single
                                        interface. It helps you use more impressive visuals in your
                                        projects.
                                    </p>
                                    <router-link to="/use-case-details">
                                        Learn More
                                    </router-link>
                                </div>
                            </div>
                            <div class="case__slider-single-h-e swiper-slide">
                                <div class="content">
                                    <h4 class="h4">Resume Builder</h4>
                                    <p>
                                        Create professional and impressive
                                        resumes. With its extreme features, it helps you organize and present your
                                        ideas to achieve your career goals.


                                    </p>
                                    <router-link to="/use-case-details">
                                        Learn More
                                    </router-link>
                                </div>
                            </div>
                            <div class="case__slider-single-h-e swiper-slide">
                                <div class="content">
                                    <h4 class="h4">Royalty Free Image Gen/Finder</h4>
                                    <p>
                                        Find quickly and easily create your royalty-free images. It provides high-quality, freely usable
                                        images for your projects.
                                    </p>
                                    <router-link to="/use-case-details">
                                        Learn More
                                    </router-link>
                                </div>
                            </div>
                            <div class="case__slider-single-h-e swiper-slide">
                                <div class="content">
                                    <h4 class="h4">Code Assistant</h4>
                                    <p>
                                        Accelerates your coding and development processes.
                                        By enriching information and ideas, it helps you create more efficient code.
                                    </p>
                                    <router-link to="/use-case-details">
                                        Learn More
                                    </router-link>
                                </div>
                            </div>
                            <div class="case__slider-single-h-e swiper-slide">
                                <div class="content">
                                    <h4 class="h4">Screenshot to Code</h4>
                                    <p>
                                        Convert quickly and accurately converts screenshots
                                        into code. This helps you save time in your projects and progress faster.
                                    </p>
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
    </section>
</template>

<script>
import Swiper from 'swiper';
import 'swiper/swiper-bundle.css';

export default {
    name: "WhatWeDo",
    mounted() {
        new Swiper('.case__slider-h-e', {
            slidesPerView: 'auto',
            spaceBetween: 30,
            loop: true,
            speed: 1000,
            autoplay: {
                delay: 4000,
            },
            navigation: {
                nextEl: '.next-h-e-case',
                prevEl: '.prev-h-e-case',
            },
        });
    }
}
</script>

<style>
.case__slider-h-e {
    overflow: hidden;
}
</style>