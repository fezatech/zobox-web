<template>
    <div>
        <div class="my-app">
            <Header :logo-src="require('@/assets/images/logo-black.png')" />
            <PageHeader page-title="Latest News" />
            <section class="section blog-main pb-0">
                <div class="container">
                    <div class="row items-gap">
                        <div class="col-12 col-xl-8">
                            <div class="blog-main__content">
                                <div class="blog-main__single">
                                    <div class="thumb">
                                        <div class="thumb-link wow fadeInUp" data-wow-duration="600ms"
                                            data-wow-delay="600ms">
                                            <router-link to="/blog-details">
                                                <img :src="require('@/assets/images/news/eight.png')" alt="Image">
                                            </router-link>
                                        </div>
                                        <div class="meta">
                                            <div class="meta__left">
                                                <p>
                                                    <strong>Written by:</strong>
                                                    FEZA.TECH
                                                </p>
                                                <span></span>
                                                <p>10/01/2024</p>
                                            </div>
                                            <div class="meta__right">
                                                <router-link to="/blog-two">LLM</router-link>
                                                <router-link to="/blog-two">Art</router-link>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="content wow fadeInUp" data-wow-duration="600ms" data-wow-delay="900ms">
                                        <h4 class="h4">
                                            <router-link to="/blog-details">
                                                With OpenAI's Innovative Technology Brings Sora Text to Real Life!
                                            </router-link>
                                        </h4>
                                        <p>
                                            OpenAI, which has made a name for itself with its groundbreaking work in the field of artificial intelligence, now offers the ability to produce video from text to users with its new artificial intelligence model called Sora.
                                        </p>
                                        <div class="cta">
                                            <router-link to="/blog-details">
                                                <i class="fa-solid fa-arrow-right-long"></i>
                                            </router-link>
                                        </div>
                                    </div>
                                </div>
                                <div class="blog-main__single">
                                    <div class="thumb">
                                        <div class="thumb-link wow fadeInUp" data-wow-duration="600ms"
                                            data-wow-delay="600ms">
                                            <router-link to="/blog-details">
                                                <img :src="require('@/assets/images/news/nine.png')" alt="Image">
                                            </router-link>
                                            <div class="video-wrap">
                                                <a href="javascript:void(0)" @click="showModal = true"
                                                    class="video-btn">
                                                    <i class="fa-solid fa-play"></i>
                                                </a>
                                            </div>
                                            <div class="modal-overlay" v-if="showModal">
                                                <iframe width="100%" height="100%"
                                                    src="https://www.youtube.com/embed/RvreULjnzFo"
                                                    title="YouTube video player" frameborder="0"
                                                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                                                    allowfullscreen>
                                                </iframe>
                                                <button @click="showModal = false">
                                                    Close
                                                </button>
                                            </div>
                                        </div>
                                        <div class="meta">
                                            <div class="meta__left">
                                                <p>
                                                    <strong>Written by:</strong>
                                                    FEZA.TECH
                                                </p>
                                                <span></span>
                                                <p>06/01/2024</p>
                                            </div>
                                            <div class="meta__right">
                                                <router-link to="/blog-two">LLM</router-link>
                                                <router-link to="/blog-two">AI World</router-link>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="content wow fadeInUp" data-wow-duration="600ms" data-wow-delay="900ms">
                                        <h4 class="h4">
                                            <router-link to="/blog-details">
                                                Turkish Large Language Model "T3.AILE" Announced: Anyone Who Wants Can
                                                Contribute
                                            </router-link>
                                        </h4>
                                        <p>
                                            T3 Foundation officially announced T3 AI'LE, a GPT 4-like native major language model.
                                            Anyone who wishes can voluntarily contribute to T3 AI, the details of which we have very little information about yet.
                                        </p>
                                        <div class="cta">
                                            <router-link to="/blog-details">
                                                <i class="fa-solid fa-arrow-right-long"></i>
                                            </router-link>
                                        </div>
                                    </div>
                                </div>
                                <div class="blog-main__single">
                                    <div class="thumb">
                                        <div class="thumb-radio wow fadeInUp" data-wow-duration="600ms"
                                            data-wow-delay="600ms">
                                            <h4 class="h4">This audio is created by ZOBOX.AI </h4>
                                            <div class="radio">
                                                <div class="audio-player">
                                                    <audio controls>
                                                        <source
                                                            src="https://ia800905.us.archive.org/19/items/FREE_background_music_dhalius/backsound.mp3"
                                                            type="audio/mp3">
                                                    </audio>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="meta">
                                            <div class="meta__left">
                                                <p>
                                                    <strong>Written by:</strong>
                                                    FEZA.TECH
                                                </p>
                                                <span></span>
                                                <p>10/01/2024</p>
                                            </div>
                                            <div class="meta__right">
                                                <router-link to="/blog-two">Nature</router-link>
                                                <router-link to="/blog-two">Health</router-link>
                                            </div>
                                        </div>
                                    </div>
                                    <!-- <div class="content wow fadeInUp" data-wow-duration="600ms" data-wow-delay="600ms">
                                        <h4 class="h4">
                                            <router-link to="/blog-details">
                                                There are also natural sources of methane - from
                                            </router-link>
                                        </h4>
                                        <p>
                                            Daily Star News published on Feb 2nd, 2022, Sangbad
                                            Protidin dated January 31st, 2022 and HRCBM's
                                            investigation. Bangladesh again witnessing uptick in
                                            violence against minorities in the country.
                                        </p>
                                        <div class="cta">
                                            <router-link to="/blog-details">
                                                <i class="fa-solid fa-arrow-right-long"></i>
                                            </router-link>
                                        </div>
                                    </div> -->
                                </div>
                                <div class="pagination-wrapper">
                                    <ul class="pagination">
                                        <li>
                                            <router-link to="/blog-two" class="active">01</router-link>
                                        </li>
                                        <!-- <li>
                                            <router-link to="/blog-two">02</router-link>
                                        </li> -->
                                        <!-- <li>
                                            <router-link to="/blog-two">03</router-link>
                                        </li> -->
                                        <li>
                                            <button>
                                                <i class="fa-solid fa-arrow-right-long"></i>
                                            </button>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-xl-4">
                            <div class="blog-main__sidebar">
                                <div class="widget wow fadeInUp" data-wow-duration="600ms" data-wow-delay="600ms">
                                    <div class="widget__head">
                                        <h5 class="h5">Search</h5>
                                    </div>
                                    <div class="widget-search">
                                        <form action="#" method="post">
                                            <div class="form-group-input">
                                                <input type="search" name="blog-search" id="blogSearch"
                                                    placeholder="Search here. . .">
                                                <button type="submit">
                                                    <i class="fa-solid fa-magnifying-glass"></i>
                                                </button>
                                            </div>
                                        </form>
                                    </div>
                                </div>
                                <div class="widget wow fadeInUp" data-wow-duration="600ms" data-wow-delay="600ms">
                                    <div class="widget__head">
                                        <h5 class="h5">Categories</h5>
                                    </div>
                                    <div class="widget__list">
                                        <ul>
                                            <li>
                                                <router-link to="/blog-two">LLM Projects</router-link>
                                            </li>
                                            <li>
                                                <router-link to="/blog-two">AI World</router-link>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="widget">
                                    <div class="widget__head">
                                        <h5 class="h5">Recent Posts</h5>
                                    </div>
                                    <div class="widget__latest">
                                        <div class="latest-single wow fadeInUp" data-wow-duration="600ms"
                                            data-wow-delay="600ms">
                                            <div class="latest-thumb">
                                                <router-link to="/blog-details">
                                                    <img :src="require('@/assets/images/news/eight_two.png')" alt="Image">
                                                </router-link>
                                            </div>
                                            <div class="latest-content">
                                                <p>10/01/2024</p>
                                                <p>
                                                    <router-link to="/blog-details">
                                                        With OpenAI's Innovative Technology Brings Sora Text to Real Life!
                                                    </router-link>
                                                </p>
                                            </div>
                                        </div>
                                        <div class="latest-single wow fadeInUp" data-wow-duration="600ms"
                                            data-wow-delay="900ms">
                                            <div class="latest-thumb">
                                                <router-link to="/blog-details">
                                                    <img :src="require('@/assets/images/news/eleven.png')" alt="Image">
                                                </router-link>
                                            </div>
                                            <div class="latest-content">
                                                <p>06/01/2024</p>
                                                <p>
                                                    <router-link to="/blog-details">
                                                        Turkish Large Language Model "T3.AILE" Announced: Anyone Who Wants Can Contribute
                                                    </router-link>
                                                </p>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="widget wow fadeInUp" data-wow-duration="600ms" data-wow-delay="600ms">
                                    <div class="widget__head">
                                        <h5 class="h5">Tags</h5>
                                    </div>
                                    <div class="widget__tags">
                                        <ul>
                                            <li>
                                                <router-link to="/blog-two">software</router-link>
                                            </li>
                                            <li>
                                                <router-link to="/blog-two">creative</router-link>
                                            </li>
                                            <li>
                                                <router-link to="/blog-two">AI art</router-link>
                                            </li>
                                            <li>
                                                <router-link to="/blog-two">business</router-link>
                                            </li>
                                            <li>
                                                <router-link to="/blog-two">artifical intellegence</router-link>
                                            </li>
                                            <li>
                                                <router-link to="/blog-two">education</router-link>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                                <div class="widget widget-big wow fadeInUp" data-wow-duration="600ms"
                                    data-wow-delay="600ms">
                                    <router-link to="/blog-two">
                                        <img :src="require('@/assets/images/news/fourteen.png')" alt="Image">
                                    </router-link>
                                    <router-link to="/blog-two" style="display: flex; justify-content: center;">
                                        <h5 class="h5">Click to Review Blogs</h5>
                                    </router-link>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <Footer class="footer-light" />
        </div>
        <BackToTop />
        <!-- modal overlay -->

    </div>
</template>

<script>
import Header from '../components/layout/Header.vue'
import PageHeader from '../components/layout/PageHeader.vue'
import Footer from '../components/layout/Footer.vue'
import BackToTop from '../components/common/BackToTop.vue'
export default {
    name: "Blog",
    components: {
        Header,
        PageHeader,
        Footer,
        BackToTop
    },
    data() {
        return {
            showModal: false,
        };
    },
};
</script>

<style scoped>
.modal-overlay {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    z-index: 998;
    width: 100%;
    height: 100%;
    background: #000000;
    cursor: pointer;
}

.modal-overlay button {
    position: absolute;
    bottom: 8px;
    right: 0;
    z-index: 1000;
    background: rgba(23, 23, 23, .8);
    border: none;
    color: white;
    font-size: 16px;
    padding: 8px 30px;
}
</style>