<template>
    <footer class="footer-two section bg-img">
        <div class="container">
            <div class="row items-gap-two">
                <div class="col-12 col-sm-6 col-xl-4 col-xxl-5">
                    <div class="footer-two__single bt wow fadeInUp" data-wow-duration="600ms">
                        <router-link to="/" class="logo">
                            <img :src="require('@/assets/images/logo.png')" alt="Image">
                        </router-link>
                        <p>
                            Copyright &copy;
                            <span id="copyYear"></span>
                            <router-link to="/">FEZA.TECH</router-link>
                        </p>
                        <div class="social">
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
                <div class="col-12 col-sm-6 col-xl-2 col-xxl-2">
                    <div class="footer-two__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="200ms">
                        <h5 class="h5">About tech AI</h5>
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
                <div class="col-12 col-sm-6 col-xl-2 col-xxl-2">
                    <div class="footer-two__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="400ms">
                        <h5 class="h5">Free Tools</h5>
                        <ul>
                            <li>
                                <a href="javascript:void(0)"> AI Article Writer</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Paraphrasing Tool</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)"> Sentence Expander</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)"> Text SummarizerAI</a>
                            </li>
                            <li>
                                <a href="javascript:void(0)">Art Generator</a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-12 col-sm-6 col-xl-4 col-xxl-3">
                    <div class="footer-two__single wow fadeInUp" data-wow-duration="600ms" data-wow-delay="600ms">
                        <h5 class="h5">Ready to unlock your full potential?</h5>
                        <div class="footer-two__form">
                            <h6 class="h6">Subscribe E-Mail List</h6>
                            <form action="#" method="post">
                                <div class="mail-group">
                                    <input type="email" name="subscribe-news" id="subscribeNews"
                                        placeholder="Enter Mail" required>
                                    <button type="submit" aria-label="subscribe to our newsletter">
                                        <i class="fa-regular fa-paper-plane"></i>
                                    </button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
    export default {
        name: "Footer2",
        mounted(){
            document.getElementById('copyYear').textContent = new Date().getFullYear();
        }
    };
</script>

<style>
    .footer-two {
        background-image: url('~@/assets/images/footer-two-bg.png');
    }

    .home-two-light .footer-two {
        background-image: url('~@/assets/images/footer-two-bg-light.png');
    }
</style>