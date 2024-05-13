<template>
<section class="language pb-0">
    <div class="language__slider">
        <div class="swiper-wrapper">
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Food &amp; Drink
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Technology
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Business &amp; Office
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Wallpapers
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Beauty &amp; Fashion
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Home Decore
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Interior Design
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Sky Dive Human
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Air Business Class
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Friends Hangouts
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Luxury Hotel
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Wedding Couple
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Winter Nature
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    4K Wallpaper
                </router-link>
            </div>
            <div class="language__slider-single swiper-slide">
                <router-link to="/use-case">
                    Games
                </router-link>
            </div>
        </div>
    </div>
    <div dir="rtl">
        <div class="language__slider-rtl">
            <div class="swiper-wrapper">
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Food &amp; Drink
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Technology
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Business &amp; Office
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Wallpapers
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Beauty &amp; Fashion
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Home Decore
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Interior Design
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Sky Dive Human
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Air Business Class
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Friends Hangouts
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Luxury Hotel
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Wedding Couple
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Winter Nature
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        4K Wallpaper
                    </router-link>
                </div>
                <div class="language__slider-single swiper-slide">
                    <router-link to="/use-case">
                        Games
                    </router-link>
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
        name: "UseCase",
        mounted() {
            new Swiper('.language__slider', {
                slidesPerView: 'auto',
                slidesPerGroup: 12,
                loop: true,
                speed: 80000,
                easing: 'linear',
                autoplay: {
                    delay: 0,
                },
                spaceBetween: 30,
            });

            new Swiper('.language__slider-rtl', {
                slidesPerView: 'auto',
                slidesPerGroup: 12,
                loop: true,
                speed: 80000,
                easing: 'linear',
                autoplay: {
                    delay: 0,
                },
                spaceBetween: 30,
            });
        }
    };
</script>