<template>
    <section class="section tour">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-12 col-xl-6">
                    <div class="section__header wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <h2 class="h2">Take a quick tour of ZOBOX</h2>
                        <p class="max-6">
                            Watch This Video to Learn All About AI Tools and How to Use Them
                        </p>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="tour__content wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <div class="video-frame"></div>
                        <video muted loop autoplay controls>
                            <source :src="require('@/assets/images/video/video.mp4')" type="video/mp4">
                        </video>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12">
                    <div class="tour__content-cta wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <div class="trust">
                            <div class="review">
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                                <i class="fa-solid fa-star"></i>
                            </div>
                            <p class="fw-7">Test it for free and get feedback to us</p>
                        </div>
                        <div class="action">
                            <router-link to="/contact-us" class="btn btn--primary">
                                start free now
                            </router-link>
                        </div>
                        <img :src="require('@/assets/images/frame-two.png')" alt="Image" class="frame">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Tour",
};
</script>

<style scoped>
.video-frame {
    background-image: url('~@/assets/images/frame.png');
    position: absolute;
    top: 0px;
    left: 0px;
    width: 100%;
    height: 100%;
    z-index: -1;
    background-size: contain;
    background-repeat: no-repeat;
}
</style>