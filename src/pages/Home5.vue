<template>
	<div>
		<div class="my-app home-five">
            <TopHeader />
			<Header class="header--dark" :logo-src="require('@/assets/images/home-four/logo.png')"/>
			<MobileMenu />
			<Banner/>
			<Case />
            <FAQ />
			<CTA />
			<Footer :logo-src="require('@/assets/images/home-four/logo.png')"/>
		</div>
		<BackToTop />
	</div>
</template>

<script>
import TopHeader from '../components/page_components/home-5/TopHeader.vue'
import Header from '../components/layout/Header.vue'
import MobileMenu from '../components/layout/MobileMenu.vue'
import Banner from '../components/page_components/home-5/Banner.vue'
import Work from '../components/page_components/home-5/Work.vue'
import FAQ from '../components/page_components/home-5/FAQ.vue'
import Case from '../components/page_components/home/Case.vue'
import Review from '../components/page_components/home/Review.vue'
import CTA from '../components/page_components/home-5/CTA.vue'
import Footer from '../components/page_components/home-5/Footer.vue'
import BackToTop from '../components/common/BackToTop.vue'
	export default {
		name: "Home",
		components: {
            TopHeader,
			Header,
			MobileMenu,
			Banner,
			FAQ,
			Case,
			CTA,
			Footer,
			BackToTop
		},
	};
</script>
