<template>
	<div>
		<div class="my-app">
			<Header :logo-src="require('@/assets/images/logo.png')" />
			<PageHeader page-title="About TechAI" />
			<Try />
			<Footer class="footer-light" />
		</div>
		<BackToTop />
	</div>
</template>

<script>
import Header from '../components/layout/Header.vue'
import PageHeader from '../components/layout/PageHeader.vue'
import Try from '../components/page_components/Try/Try.vue'
import Footer from '../components/layout/Footer.vue'
import BackToTop from '../components/common/BackToTop.vue'
export default {
	name: "HomeLight",
	components: {
		Try,
	},
};
</script>