<template>
    <section class="section testimonial-three review">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="section__header wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <h2 class="h2">Our Customer Reviews</h2>
                    </div>
                </div>
            </div>
            <div class="row items-gap align-items-center testimonial-three__slider-container">
                <div class="col-12 col-lg-6">
                    <div class="testimonial-three__slider swiper-container">
                        <div class="swiper-wrapper">
                            <div class="review__single swiper-slide wow fadeInUp" data-wow-duration="600ms">
                                <div class="review-head">
                                    <div class="review__icons">
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                    </div>
                                    <img :src="require('@/assets/images/review/icon-one.png')" alt="Image">
                                </div>
                                <div class="review-content">
                                    <p class="fw-7">
                                        ZOBOX-LLM enables us to save thousands of dollars per week. We create and write
                                        50-100
                                        unique SEO-focused content guides every month. With Tech.ai, we now generate
                                        guides,
                                        outlines, and complete content first.This AI integration capability
                                        significantly streamlines our work.
                                    </p>
                                </div>
                                <!-- <div class="review-meta">
                                    <div class="thumb">
                                        <img :src="require('@/assets/images/review/one.png')" alt="Image">
                                    </div>
                                    <div class="content">
                                        <p class="h6">Rex A. Munoz</p>
                                        <p>CEO, uSERP</p>
                                    </div>
                                </div> -->
                            </div>
                            <div class="review__single swiper-slide wow fadeInUp" data-wow-duration="600ms"
                                data-wow-delay="200ms">
                                <div class="review-head">
                                    <div class="review__icons">
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                    </div>
                                    <img :src="require('@/assets/images/review/icon-two.png')" alt="Image">
                                </div>
                                <div class="review-content">
                                    <p class="fw-7">
                                        ZOBOX's translation capabilities truly surprised me! Dealing with documents in
                                different languages is a part of my job, and thanks to ZOBOX.AI, my translation process
                                has become much faster and more efficient. It's definitely an excellent tool!
                                    </p>
                                </div>
                                <!-- <div class="review-meta">
                                    <div class="thumb">
                                        <img :src="require('@/assets/images/review/two.png')" alt="Image">
                                    </div>
                                    <div class="content">
                                        <p class="h6">Nicholas Natteau</p>
                                        <p>CEO, uSERP</p>
                                    </div>
                                </div> -->
                            </div>
                            <div class="review__single swiper-slide wow fadeInUp" data-wow-duration="600ms"
                                data-wow-delay="400ms">
                                <div class="review-head">
                                    <div class="review__icons">
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                    </div>
                                    <img :src="require('@/assets/images/review/icon-three.png')" alt="Image">
                                </div>
                                <div class="review-content">
                                    <p class="fw-7">
                                        ZOBOX.AI's text generation abilities are truly impressive. I constantly need to produce
                                content for blog posts, and ZOBOX.AI's creative suggestions and fluent texts constantly
                                amaze me. Now, the content creation process is both more enjoyable and more efficient!
                                    </p>
                                </div>
                                <!-- <div class="review-meta">
                                    <div class="thumb">
                                        <img :src="require('@/assets/images/review/two.png')" alt="Image">
                                    </div>
                                    <div class="content">
                                        <p class="h6">Jeremy Moser</p>
                                        <p>CEO, uSERP</p>
                                    </div>
                                </div> -->
                            </div>
                            <div class="review__single swiper-slide wow fadeInUp" data-wow-duration="600ms"
                                data-wow-delay="600ms">
                                <div class="review-head">
                                    <div class="review__icons">
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                        <i class="fa-solid fa-star"></i>
                                    </div>
                                    <img :src="require('@/assets/images/review/icon-one.png')" alt="Image">
                                </div>
                                <div class="review-content">
                                    <p class="fw-7">
                                        I'm really excited to explore ZOBOX.AI's potential on social media. I deal with constant
                                customer reports and notes, and thanks to ZOBOX.AI's natural language processing
                                capabilities, understanding and analyzing these documents has become much easier.
                                    </p>
                                </div>
                                <!-- <div class="review-meta">
                                    <div class="thumb">
                                        <img :src="require('@/assets/images/review/three.png')" alt="Image">
                                    </div>
                                    <div class="content">
                                        <p class="h6">Angela R. Nolan</p>
                                        <p>CEO, uSERP</p>
                                    </div>
                                </div> -->
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-lg-6">
                    <div class="testimonial-three-thumb">
                        <img :src="require('@/assets/images/review/thumb.png')" alt="Image">
                        <div class="testimonial-switch">
                            <button class="prev-testimonial-three" aria-label="previous slider">
                                <i class="fa-solid fa-angle-up"></i>
                            </button>
                            <button class="next-testimonial-three" aria-label="next slider">
                                <i class="fa-solid fa-angle-down"></i>
                            </button>
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
    name: "Testimonial",
    mounted() {
        new Swiper('.swiper-container', {
            slidesPerView: 1,
            slidesPerGroup: 1,
            spaceBetween: 20,
            loop: true,
            speed: 1000,
            direction: 'horizontal',
            autoplay: {
                delay: 4000,
            },
            navigation: {
                nextEl: '.next-testimonial-three',
                prevEl: '.prev-testimonial-three',
            },
            breakpoints: {
                1400: {
                    slidesPerView: 2,
                    direction: 'vertical',
                },
                992: {
                    direction: 'vertical',
                }
            }
        });
    }
}
</script>

<style scoped>
.testimonial-three__slider {
    overflow: hidden;
    user-select: none;
}

@media screen and (min-width: 992px) {
    .testimonial-three__slider {
        height: 713px;
    }
}
</style>