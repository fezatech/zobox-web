<template>
    <section class="section clone about-main">
        <div class="container">
            <div class="row items-gap align-items-center">
                <div class="col-12 col-lg-6">
                    <div class="about__thumb wow fadeInLeft" data-wow-duration="600ms" data-wow-delay="300ms">
                        <img :src="require('@/assets/images/about-thumb.png')" alt="Image">
                    </div>
                </div>
                <div class="col-12 col-lg-6">
                    <div class="clone__content section__content wow fadeInUp" data-wow-duration="600ms"
                        data-wow-delay="600ms">
                        <h2 class="h2">Enabling Available AI for Everyone</h2>
                        <div class="paragraph">
                            <p class="fw-5 text-lg">
                                Use artificial intelligence tools that suit your needs in an integrated manner under a
                                single workspace.
                            </p>
                            <p>
                                By simplifying complex technologies, we strive to enable individuals and businesses of
                                all sizes to benefit from the latest advances in artificial intelligence. Our tools
                                simplify and speed up workflows, encourage creativity, and enable others to create new
                                products.
                            </p>
                        </div>
                        <ul>
                            <li>
                                <i class="fa-solid fa-check"></i>
                                Easy-to-Use
                            </li>
                            <li>
                                <i class="fa-solid fa-check"></i>
                                Integrated Workspace
                            </li>
                            <li>
                                <i class="fa-solid fa-check"></i>
                                Tailored Features
                            </li>
                        </ul>
                        <div class="tour__content-cta">
                            <div class="trust">
                                <div class="review">
                                    <i class="fa-solid fa-star"></i>
                                    <i class="fa-solid fa-star"></i>
                                    <i class="fa-solid fa-star"></i>
                                    <i class="fa-solid fa-star"></i>
                                    <i class="fa-solid fa-star"></i>
                                </div>
                                <p class="fw-7">Rated Excellent on Trustpilot</p>
                            </div>
                            <div class="action">
                                <router-link to="/contact-us" class="btn btn--primary">
                                    request A Demo - its free
                                </router-link>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "Introduction",
}
</script>