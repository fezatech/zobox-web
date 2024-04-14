<template>
    <section class="section review review-light pb-0">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-12 col-xl-8">
                    <div class="section__header wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <h2 class="h2">Our Customer Reviews</h2>
                    </div>
                </div>
            </div>
            <div class="row items-gap">
                <div class="col-12 col-lg-6">
                    <div class="review__single wow fadeInUp" data-wow-duration="600ms">
                        <div class="review-head">
                            <div style="display: flex; justify-content: center; align-items: center;">
                                <img :src="require('@/assets/images/review/icon-one.png')" alt="Image">
                                <div class="content" style="margin-left: 20%;">
                                    <p class="h6">Mr. Serhat</p>
                                </div>
                            </div>
                            <div class="review__icons">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </div>
                        </div>
                        <div class="review-content">
                            <p class="fw-7">
                                When we started using ZOBOX, we saw once again the great potential in the world of
                                artificial intelligence. Even at the MVP stage, tools like the Photo Edit Tool and
                                Resume Builder offered by ZOBOX have greatly streamlined our workflows. ZOBOX's flexible
                                structure and user-friendly interface are of great benefit even for small businesses. We
                                look forward to what ZOBOX will deliver in the future!
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
                </div>
                <div class="col-12 col-lg-6">
                    <div class="review__single wow fadeInUp" data-wow-duration="600ms">
                        <div class="review-head">
                            <div style="display: flex; justify-content: center; align-items: center;">
                                <img :src="require('@/assets/images/review/icon-two.png')" alt="Image">
                                <div class="content" style="margin-left: 20%;">
                                    <p class="h6">Mrs. Merve</p>
                                </div>
                            </div>
                            <div class="review__icons">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </div>
                        </div>
                        <div class="review-content">
                            <p class="fw-7">
                                We met ZOBOX at an entrepreneurship summit at the MVP stage. I have full faith that this
                                startup, which offers all the artificial intelligence tools needed in a single workspace
                                and aims to provide a harmonious integration, will be very successful in the future.
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
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Review",
}
</script>