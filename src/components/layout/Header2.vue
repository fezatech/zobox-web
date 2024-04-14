<template>
	<header :class="{ 'header-active': scrollPosition >= 100, }" class="header header-two">
		<div class="container">
			<div class="row">
				<div class="col-lg-12">
					<nav class="nav">
						<div class="nav__content">
							<div class="nav__logo">
								<router-link to="/">
									<img :src="require('@/assets/images/logo-three.png')" alt="Logo" />
								</router-link>
							</div>
							<div class="nav__menu">
								<ul class="nav__menu-items">
									<li class="nav__menu-item nav__menu-item--dropdown">
										<a href="javascript:void(0)" class="nav__menu-link nav__menu-link--dropdown">
											AI Tools
										</a>
										<div class="nav__dropdown nav__dropdown--alt">
											<ul>
												<a href="/">
													<li class="atery" style="font-size: 28px;">
														ZOBOX <br>AI TOOLS
													</li>
												</a>
											</ul>
											<ul>
												<li>
													<router-link to="/" class="nav__dropdown-item hide-nav">
														Voice Over
													</router-link>
												</li>
												<li>
													<router-link to="/content_writer" class="nav__dropdown-item hide-nav">
														Content Writer
													</router-link>
												</li>
												<li>
													<router-link to="/photo_edit_tool" class="nav__dropdown-item hide-nav">
														Photo Edit Tool
													</router-link>
												</li>
												<li>
													<router-link to="/resume_builder" class="nav__dropdown-item hide-nav">
														Resume Builder
													</router-link>
												</li>
												<li>
													<router-link to="/copy_writing" class="nav__dropdown-item hide-nav">
														Copy Writing
													</router-link>
												</li>
												<li>
													<router-link to="/write_code" class="nav__dropdown-item hide-nav">
														Write Code
													</router-link>
												</li>
												<li>
													<router-link to="/image_generator" class="nav__dropdown-item hide-nav">
														Image Generator
													</router-link>
												</li>
												<li>
													<router-link to="/digital_agency" class="nav__dropdown-item hide-nav">
														Digital Agency
													</router-link>
												</li>
												<li>
													<router-link to="/video_creation" class="nav__dropdown-item hide-nav">
														Video Creation
													</router-link>
												</li>
												<li>
													<router-link to="/personel_consultan"
														class="nav__dropdown-item hide-nav">
														Personal Consultant
													</router-link>
												</li>
											</ul>
										</div>
									</li>
									<li class="nav__menu-item">
										<router-link to="/about" class="nav__menu-link hide-nav">About
											Us</router-link>
									</li>
									<li class="nav__menu-item nav__menu-item--dropdown">
										<a href="javascript:void(0)" class="nav__menu-link nav__menu-link--dropdown">
											Use
											Case
										</a>
										<ul class="nav__dropdown">
											<li>
												<router-link class="nav__dropdown-item hide-nav" to="/use-case">
													Use
													Case
												</router-link>
											</li>
											<li>
												<router-link class="nav__dropdown-item hide-nav" to="/use-case-details">
													Use
													Case
													Details
												</router-link>
											</li>
										</ul>
									</li>
									<li class="nav__menu-item nav__menu-item--dropdown">
										<a href="javascript:void(0)" class="nav__menu-link nav__menu-link--dropdown">
											Pages
										</a>
										<ul class="nav__dropdown">
											<li>
												<router-link to="/404"
													class="nav__dropdown-item hide-nav">Error</router-link>
											</li>
											<li>
												<router-link to="/sign-up" class="nav__dropdown-item hide-nav">
													Sign
													Up
												</router-link>
											</li>
											<li>
												<router-link to="/sign-in" class="nav__dropdown-item hide-nav">
													Sign
													In
												</router-link>
											</li>
											<li>
												<router-link to="/teams" class="nav__dropdown-item hide-nav">
													Our
													Teams
												</router-link>
											</li>
											<li>
												<router-link to="/about" class="nav__dropdown-item hide-nav">
													About
													Us
												</router-link>
											</li>
											<li>
												<router-link to="/contact-us" class="nav__dropdown-item hide-nav">
													Contact
													Us
												</router-link>
											</li>
										</ul>
									</li>
									<li class="nav__menu-item nav__menu-item--dropdown">
										<a href="javascript:void(0)" class="nav__menu-link nav__menu-link--dropdown">
											Blog
										</a>
										<ul class="nav__dropdown">
											<li>
												<router-link to="/blog" class="nav__dropdown-item hide-nav">
													Blog
													Layout
													One
												</router-link>
											</li>
											<li>
												<router-link to="/blog-two" class="nav__dropdown-item hide-nav">
													Blog
													Layout
													Two
												</router-link>
											</li>
											<li>
												<router-link to="blog-details" class="nav__dropdown-item hide-nav">
													Blog
													Single
												</router-link>
											</li>
										</ul>
									</li>
									<li class="nav__menu-item">
										<router-link to="/contact-us" class="nav__menu-link hide-nav">Contact
											Us</router-link>
									</li>
									<li class="nav__menu-item d-block d-md-none">
										<router-link to="/sign-up" class="btn btn--septenary">
											Sign
											Up
										</router-link>
									</li>
								</ul>
								<div class="social">
									<a href="https://www.facebook.com" aria-label="social media">
										<i class="fa-brands fa-facebook-f"></i>
									</a>
									<a href="https://www.twitter.com" aria-label="social media">
										<i class="fa-brands fa-twitter"></i>
									</a>
									<a href="https://www.linkedin.com" aria-label="social media">
										<i class="fa-brands fa-linkedin-in"></i>
									</a>
									<a href="https://www.instagram.com" aria-label="social media">
										<i class="fa-brands fa-instagram"></i>
									</a>
								</div>
							</div>
							<div class="nav__uncollapsed">
								<div class="nav__uncollapsed-item d-none d-md-flex">
									<router-link to="/sign-up" class="btn btn--septenary">Sign
										Up</router-link>
								</div>
								<button class="nav__bar d-block d-xl-none">
									<span class="icon-bar top-bar"></span>
									<span class="icon-bar middle-bar"></span>
									<span class="icon-bar bottom-bar"></span>
								</button>
							</div>
						</div>
					</nav>
				</div>
			</div>
		</div>
		<div class="backdrop"></div>
	</header>
</template>

<script>
export default {
	name: "Header2",
	data: function () {
		return {
			scrollPosition: null,
		};
	},
	methods: {
		updateScroll() {
			this.scrollPosition =
				window.scrollY;
		},
	},
	mounted() {
		window.addEventListener(
			"scroll",
			this.updateScroll
		);
	},
};
</script>

<style></style>