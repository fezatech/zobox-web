<template>
    <div>
        <div class="my-app home-six home-six-dark">
            <Header class="header--light" :logo-src="require('@/assets/images/logo.png')"/>
            <MobileMenu />
            <Banner />
            <Sponsor />
            <Features />
            <FeatureTabs />
            <Pricing />
            <Feedback />
            <Feedback2 />
            <FAQ />
            <CTA />
            <Footer :logo-src="require('@/assets/images/logo.png')"/>
        </div>
        <BackToTop />
    </div>
</template>

<script>
import Header from '../components/layout/Header.vue'
import MobileMenu from '../components/layout/MobileMenu.vue'
import Banner from '../components/page_components/home-6/Banner.vue'
import Sponsor from '../components/page_components/home-6/Sponsor.vue'
import Features from '../components/page_components/home-6/Features.vue'
import FeatureTabs from '../components/page_components/home-6/FeatureTabs.vue'
import Pricing from '../components/page_components/home-6/Pricing.vue'
import Feedback from '../components/page_components/home-6/Feedback.vue'
import Feedback2 from '../components/page_components/home-6/Feedback2.vue'
import FAQ from '../components/page_components/home-6/FAQ.vue'
import CTA from '../components/page_components/home-6/CTA.vue'
import Footer from '../components/page_components/home-6/Footer.vue'
import BackToTop from '../components/common/BackToTop.vue'
    export default {
        name: "Home4",
        components: {
            Header,
            MobileMenu,
            Banner,
            Sponsor,
            Features,
            Feedback,
            FAQ,
            CTA,
            Footer,
            BackToTop
        }
    }
</script>

<style scoped>
    .home-six-dark header {
        background-image: url('~@/assets/images/home-six/header-bg.png');
    }
</style>