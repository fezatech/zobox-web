<template>
    <section class="section eraser eraser-two">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-12">
                    <div class="section__header--secondary">
                        <div class="row align-items-center items-gap">
                            <div class="col-12 col-lg-8 col-xl-6">
                                <h2 class="h2 wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                                    Why and how will ZOBOX AI Tools affect you?
                                </h2>
                            </div>
                            <div class="col-12 col-lg-4 col-xl-6">
                                <div class="cmn-pagination eraser-pagination"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="eraser__slider">
                        <div class="swiper-wrapper">
                            <div class="eraser__slider-item swiper-slide">
                                <div class="thumb">
                                    <img :src="require('@/assets/images/eraser/one.png')" alt="Image">
                                </div>
                                <div class="content">
                                    <h5 class="h5">Simple to Use</h5>
                                    <p>
                                        Advanced AI technology makes the tools extremely easy to use.
                                    </p>
                                </div>
                            </div>
                            <div class="eraser__slider-item swiper-slide">
                                <div class="thumb">
                                    <img :src="require('@/assets/images/eraser/two.png')" alt="Image">
                                </div>
                                <div class="content">
                                    <h5 class="h5">Highly Accurate</h5>
                                    <p>
                                        It provides a high level of convenience in business processes with its high
                                        accuracy rates.
                                    </p>
                                </div>
                            </div>
                            <div class="eraser__slider-item swiper-slide">
                                <div class="thumb">
                                    <img :src="require('@/assets/images/eraser/three.png')" alt="Image">
                                </div>
                                <div class="content">
                                    <h5 class="h5">Design Effectively</h5>
                                    <p>
                                        Thanks to its design suitable for user experience, it makes artificial
                                        intelligence usable for everyone.
                                    </p>
                                </div>
                            </div>
                            <div class="eraser__slider-item swiper-slide">
                                <div class="thumb">
                                    <img :src="require('@/assets/images/eraser/four.png')" alt="Image">
                                </div>
                                <div class="content">
                                    <h5 class="h5">Share Easily</h5>
                                    <p>
                                        You can easily move and use the outputs of single workspace artificial
                                        intelligence tools to another tool.
                                    </p>
                                </div>
                            </div>
                            <div class="eraser__slider-item swiper-slide">
                                <div class="thumb">
                                    <img :src="require('@/assets/images/eraser/one.png')" alt="Image">
                                </div>
                                <div class="content">
                                    <h5 class="h5">Versatile Functionality</h5>
                                    <p>
                                        Explore a wide range of functionalities tailored to meet diverse needs.
                                    </p>
                                </div>
                            </div>

                            <div class="eraser__slider-item swiper-slide">
                                <div class="thumb">
                                    <img :src="require('@/assets/images/eraser/two.png')" alt="Image">
                                </div>
                                <div class="content">
                                    <h5 class="h5">Seamless Integration</h5>
                                    <p>
                                        Whether you're using productivity suites or development environments in design
                                        or software, our AI solutions integrate seamlessly.
                                    </p>
                                </div>
                            </div>

                            <div class="eraser__slider-item swiper-slide">
                                <div class="thumb">
                                    <img :src="require('@/assets/images/eraser/three.png')" alt="Image">
                                </div>
                                <div class="content">
                                    <h5 class="h5">Customizable Options</h5>
                                    <p>
                                        With customizable options, you can adjust settings, personalize output, and
                                        fine-tune parameters to align with your unique workflow and goals.
                                    </p>
                                </div>
                            </div>

                            <div class="eraser__slider-item swiper-slide">
                                <div class="thumb">
                                    <img :src="require('@/assets/images/eraser/four.png')" alt="Image">
                                </div>
                                <div class="content">
                                    <h5 class="h5">Continuous Improvement</h5>
                                    <p>
                                        Our AI platform is continuously evolving, incorporating the latest advancements
                                        and feedback from users to deliver cutting-edge solutions and features.
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
import Swiper, { Navigation, Pagination } from 'swiper';
import 'swiper/swiper-bundle.css';

Swiper.use([Navigation, Pagination]);
export default {
    name: "Benefits",
    mounted() {
        new Swiper('.eraser__slider', {
            slidesPerView: 1,
            slidesPerGroup: 1,
            spaceBetween: 30,
            loop: true,
            speed: 1000,
            pagination: {
                el: '.eraser-pagination',
                clickable: true,
            },
            autoplay: {
                delay: 4000,
            },
            breakpoints: {
                1400: {
                    slidesPerView: 4,
                    slidesPerGroup: 2,
                },
                992: {
                    slidesPerView: 3,
                    slidesPerGroup: 2,
                },
                576: {
                    slidesPerView: 2,
                    slidesPerGroup: 2,
                },
            }
        });
    }
}
</script>

<style>
.eraser__slider {
    overflow: hidden;
    user-select: none;
}
</style>