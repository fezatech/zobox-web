<template>
    <section class="section broadcast pb-0">
        <div class="container">
            <div class="row">
                <div class="col-12 fix-scroll">
                    <div class="broadcast__inner wow fadeInUp" data-wow-duration="600ms">
                        <div class="row align-items-center items-gap-two">
                            <div class="col-12 col-xl-8 col-xxl-7">
                                <div class="section__content broadcast__inner-content">
                                    <h2 class="h2">Commercial & broadcast rights</h2>
                                    <div class="paragraph">
                                        <p>

                                            Your text-to-speech synthesized files are safely stored in the cloud. You
                                            can also create drafts later and convert any text to audio. You can produce
                                            clear, consistent, and professional voice for marketing, explainer, product,
                                            and videos.
                                        </p>
                                    </div>
                                    <div class="section__content-cta">
                                        <router-link to="/contact-us" class="btn btn--secondary">
                                            request A Demo
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-xl-4 col-xxl-5">
                                <div class="broadcast__thumb text-xl-center">
                                    <img :src="require('@/assets/images/broadcast-thumb.png')" alt="Image">
                                </div>
                            </div>
                        </div>
                        <div class="anime">
                            <img :src="require('@/assets/images/anime-three.png')" alt="Image" class="anime-one">
                            <img :src="require('@/assets/images/anime-two.png')" alt="Image" class="anime-two">
                        </div>
                    </div>
                    <div class="broadcast__inner wow fadeInUp" data-wow-duration="600ms">
                        <div class="row align-items-center items-gap-two">
                            <div class="col-12 col-xl-4 col-xxl-5">
                                <div class="broadcast__thumb text-xl-center">
                                    <img :src="require('@/assets/images/broadcast-thumb-two.png')" alt="Image">
                                </div>
                            </div>
                            <div class="col-12 col-xl-8 col-xxl-7">
                                <div class="section__content broadcast__inner-content">
                                    <h2 class="h2">Team Access for Collaboration</h2>
                                    <div class="paragraph">
                                        <p>

                                            Boost your productivity with the seamless integration of artificial
                                            intelligence applications tailored to mirror your company or team culture.
                                            Unleash the power of collaboration and efficiency with tools designed to
                                            align with your unique work environment.
                                        </p>
                                    </div>
                                    <div class="section__content-cta">
                                        <router-link to="/contact-us" class="btn btn--secondary">
                                            request a demo
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="anime">
                            <img :src="require('@/assets/images/anime-three.png')" alt="Image" class="anime-one">
                            <img :src="require('@/assets/images/anime-two.png')" alt="Image" class="anime-two">
                        </div>
                    </div>
                    <div class="broadcast__inner wow fadeInUp" data-wow-duration="600ms">
                        <div class="row align-items-center items-gap-two">
                            <div class="col-12 col-xl-8 col-xxl-7">
                                <div class="section__content broadcast__inner-content">
                                    <h2 class="h2">Insanely Powerful & Easy to Use</h2>
                                    <div class="paragraph">
                                        <p>
                                            Experience extraordinary with our extremely powerful and user-friendly AI
                                            tools. Effortlessly unlock the potential of AI by making complex tasks
                                            simple and accessible. Additionally, use integrated artificial intelligence
                                            applications with one-click outputs.
                                        </p>
                                    </div>
                                    <div class="section__content-cta">
                                        <router-link to="/contact-us" class="btn btn--secondary">
                                            request A Demo
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                            <div class="col-12 col-xl-4 col-xxl-5">
                                <div class="broadcast__thumb text-xl-center">
                                    <img :src="require('@/assets/images/broadcast-thumb-three.png')" alt="Image">
                                </div>
                            </div>
                        </div>
                        <div class="anime">
                            <img :src="require('@/assets/images/anime-three.png')" alt="Image" class="anime-one">
                            <img :src="require('@/assets/images/anime-two.png')" alt="Image" class="anime-two">
                        </div>
                    </div>
                    <div class="broadcast__inner wow fadeInUp" data-wow-duration="600ms">
                        <div class="row align-items-center items-gap-two">
                            <div class="col-12 col-xl-4 col-xxl-5">
                                <div class="broadcast__thumb text-xl-center">
                                    <img :src="require('@/assets/images/broadcast-thumb-four.png')" alt="Image">
                                </div>
                            </div>
                            <div class="col-12 col-xl-8 col-xxl-7">
                                <div class="section__content broadcast__inner-content">
                                    <h2 class="h2">Create life-like Voice clones</h2>
                                    <div class="paragraph">
                                        <p>
                                            Generate text-to-speech synthesized audio files with remarkable realism,
                                            securely stored in the cloud. Craft drafts and effortlessly convert text
                                            into audio at your convenience. Experience clear, consistent, and
                                            professional voices tailored for marketing, explainer content, product
                                            descriptions, and videos. Redefine your audio experience with lifelike voice
                                            clones that resonate with your audience.
                                        </p>
                                    </div>
                                    <div class="section__content-cta">
                                        <router-link to="/contact-us" class="btn btn--secondary">
                                            request A Demo
                                        </router-link>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="anime">
                            <img :src="require('@/assets/images/anime-three.png')" alt="Image" class="anime-one">
                            <img :src="require('@/assets/images/anime-two.png')" alt="Image" class="anime-two">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Broadcast",
};
</script>

<style>
.broadcast .broadcast__inner {
    background-image: url('~@/assets/images/broadcast-bg.png');
}
</style>