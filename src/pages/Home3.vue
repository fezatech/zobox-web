<template>
	<div>
		<div class="my-app home-dark">
			<Header class="header--dark" :logo-src="require('@/assets/images/logo.png')"/>
            <MobileMenu />
            <Banner3 />
            <Removebg />
            <Workflow />
            <Generate />
            <Eraser />
            <FAQ />
            <Testimonial />
            <Explore />
            <CTA />
            <Footer3 :logo-src="require('@/assets/images/logo.png')"/>
		</div>
		<BackToTop />
	</div>
</template>

<script>
import Header from '../components/layout/Header.vue'
import MobileMenu from '../components/layout/MobileMenu.vue'
import Banner3 from '../components/page_components/home-3/Banner3.vue'
import Removebg from '../components/page_components/home-3/Removebg.vue'
import Workflow from '../components/page_components/home-3/Workflow.vue'
import Generate from '../components/page_components/home-3/Generate.vue'
import Eraser from '../components/page_components/home-3/Eraser.vue'
import FAQ from '../components/page_components/home-3/FAQ.vue'
import Testimonial from '../components/page_components/home-3/Testimonial.vue'
import Explore from '../components/page_components/home-3/Explore.vue'
import CTA from '../components/page_components/home-3/CTA.vue'
import Footer3 from '../components/layout/Footer3.vue'
import BackToTop from '../components/common/BackToTop.vue'
	export default {
		name: "Home3",
		components: {
			Header,
            MobileMenu,
            Banner3,
            Removebg,
            Workflow,
            Generate,
            Eraser,
            FAQ,
            Testimonial,
            Explore,
            CTA,
            Footer3,
			BackToTop
		},
	};
</script>
