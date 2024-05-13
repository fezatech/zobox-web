<template>
    <footer class="footer section pb-0">
        <div class="container">
            <div class="row items-gap-two">
                <div class="col-12 col-sm-6 col-lg-3">
                    <div class="footer__single wow fadeInUp" data-wow-duration="600ms">
                        <h5 class="h5">Our Products</h5>
                        <ul>
                            <li>
                                <a href="javascript:void(0)"> ZOBOX-LLM</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)"> Image Background Remover</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)"> Audio Voice Over AI</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)"> Text Summarizer AI</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Art Generator</a>
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
                    <div class="footer__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="400ms">
                        <h5 class="h5">Use Cases</h5>
                        <ul>
                            <li>
                                <a href="javascript:void(0)"> AI Voiceover for Videos</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">E- Learning</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)"> All interactive Voice</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)"> Auto Accessibility</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">YouTube Videos</a>
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
        <div class="bg-img fer">
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <div class="copyright-inner">
                            <div class="row items-gap align-items-center">
                                <div class="col-12 col-lg-3">
                                    <div class="logo text-center text-lg-start">
                                        <router-link to="/">
                                            <img :src="LogoSrc" alt="Image">
                                        </router-link>
                                    </div>
                                </div>
                                <div class="col-12 col-lg-6">
                                    <p class="text-center">
                                        Copyright &copy;
                                        <span id="copyYear"></span>
                                        <router-link to="/">ZOBOX.AI</router-link>
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
                                        <a href="https://www.linkedin.com/company/fezateknoloji"
                                            aria-label="social media">
                                            <i class="fa-brands fa-linkedin-in"></i>
                                        </a>
                                        <a href="https://www.instagram.com/feza.tech" aria-label="social media">
                                            <i class="fa-brands fa-instagram"></i>
                                        </a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer",
    mounted() {
        document.getElementById('copyYear').textContent = new Date().getFullYear();
    },
    props: {
        LogoSrc: {
            type: String,
            required: true,
        },
    },
};
</script>

<style scoped>
.bg-img.fer {
    background-image: url('~@/assets/images/home-six/ft.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
}
</style>