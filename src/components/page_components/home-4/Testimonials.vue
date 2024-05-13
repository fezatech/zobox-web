<template>
    <section class="section pb-0 testimonial">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="section__header wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <h4 class="h2">professionals & teams choose ZOBOX.AI.</h4>
                    </div>
                </div>
            </div>
        </div>
        <div class="testimonial__slider-wrapper container">
            <div class="testimonial__slider">
                <div class="swiper-wrapper">
                    <div class="review__single swiper-slide">
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
                                ZOBOX-LLM enables us to save thousands of dollars per week. We create and write 50-100
                                unique SEO-focused content guides every month. With Tech.ai, we now generate guides,
                                outlines, and complete content first.This AI integration capability significantly streamlines our work.
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
                    <div class="review__single swiper-slide">
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
                    <div class="review__single swiper-slide">
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
                    <div class="review__single swiper-slide">
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
            <div class="testimonial__arrows">
                <button aria-label="previous slide" class="slide-btn prev-testimonial">
                    <i class="tech-left-angle"></i>
                </button>
                <button aria-label="next slide" class="slide-btn next-testimonial">
                    <i class="tech-right-angle"></i>
                </button>
            </div>
        </div>
    </section>
</template>

<script>
    import Swiper from 'swiper';
    import 'swiper/swiper-bundle.css';

    export default {
        name: "Testimonials",
        mounted() {
            new Swiper('.testimonial__slider', {
                slidesPerView: 'auto',
                centeredSlides: true,
                slidesPerGroup: 1,
                spaceBetween: 30,
                loop: true,
                speed: 1000,
                autoplay: {
                    delay: 4000,
                },
                breakpoints: {
                    1200: {
                        slidesPerView: 3,
                    },
                }
            });
        }
    }
</script>

<style scoped>
    .testimonial .testimonial__arrows {
        z-index: 100;
    }
    .swiper-slide-active {
        opacity: 0.8;
    }
    .swiper-slide-prev,
    .swiper-slide-next {
        opacity: 0.5;
    }
</style>