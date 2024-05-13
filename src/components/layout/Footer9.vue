<template>
    <footer class="footer footer-three section pb-0">
        <div class="container">
            <div class="row items-gap align-items-center top-break wow fadeInUp" data-wow-duration="600ms"
                data-wow-delay="300ms">
                <div class="col-12 col-lg-3">
                    <div class="logo">
                        <router-link to="/">
                            <img :src="LogoURL" alt="Image">
                        </router-link>
                    </div>
                </div>
                <div class="col-12 col-lg-6 col-xxl-5 offset-xxl-1">
                    <p>
                        Video Creation Tool offers you the opportunity to create videos from scratch with the prompt you
                        give to artificial intelligence. It offers the opportunity to edit as you wish from a single
                        platform.
                        We are currently working on it.
                    </p>
                </div>
                <div class="col-12 col-lg-3">
                    <div class="social justify-content-center justify-content-lg-end">
                        <a href="https://github.com/feza.tech" aria-label="social media">
                            <i class="fa-brands fa-github"></i>
                        </a>
                        <a href="https://twitter.com/feza.tech" aria-label="social media">
                            <i class="fa-brands fa-twitter"></i>
                        </a>
                        <a href="https://www.linkedin.com/company/fezateknoloji" aria-label="social media">
                            <i class="fa-brands fa-linkedin-in"></i>
                        </a>
                        <a href="https://www.instagram.com/feza.tech" aria-label="social media">
                            <i class="fa-brands fa-instagram"></i>
                        </a>
                    </div>
                </div>
            </div>
            <hr id="footer-break">
            <div class="row items-gap-two">
                <div class="col-12 col-sm-6 col-lg-3">
                    <div class="footer__single wow fadeInUp" data-wow-duration="600ms">
                        <h5 class="h5">Video Creation</h5>
                        <ul>
                            <li>
                                <a href="javascript:void(0)"> Video Creator</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)"> Video Prompt Maker</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)"> Video Edit</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-12 col-sm-6 col-lg-3">
                    <div class="footer__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="200ms">
                        <h5 class="h5">About ZOBOX.AI</h5>
                        <ul>
                            <li>
                                <a href="javascript:void(0)">About</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Blog</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Sign in</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Register</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Contact</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-12 col-sm-6 col-lg-3">
                    <div class="footer__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="600ms">
                        <h5 class="h5">Support</h5>
                        <ul>
                            <li>
                                <a href="javascript:void(0)">Privacy Policy</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Terms of Service</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Cookie Policy</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">FAQ</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Helpdesk</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        <div class="copyright text-center">
            <p>
                Copyright &copy;
                <span id="copyYear"></span>
                <router-link to="/">ZOBOX.AI</router-link>
            </p>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer3",
    props: {
        LogoSrc: {
            type: String,
            required: true,
        },
    },
    computed: {
        LogoURL() {
            return this.LogoSrc;
        },
    },
    mounted() {
        document.getElementById('copyYear').textContent = new Date().getFullYear();
    }
};
</script>