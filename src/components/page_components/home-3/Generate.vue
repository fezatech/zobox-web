<template>
    <section class="section generate generate-two generate-three pb-0">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="section__header wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <h2 class="h2">Photo Edit Tool Use Cases</h2>
                    </div>
                </div>
            </div>
            <div class="row items-gap">
                <div class="col-12 col-lg-6 col-xl-5">
                    <div class="generate__content wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <div class="generate__content-btn generate__content-btn-active">
                            <div class="content">
                                <h5 class="h5">Object Extraction from Images as Layers</h5>
                                <p>
                                    You can separate, remove, and complete objects in the uploaded image as layers using
                                    artificial intelligence.
                                </p>
                            </div>
                        </div>
                        <div class="generate__content-btn">
                            <div class="content">
                                <h5 class="h5">Basic Photo Editing Tools</h5>
                                <p>
                                    You can use all basic photo editing tools such as cropping, resizing, and sharpening
                                    in a single interface.
                                </p>
                            </div>
                        </div>
                        <div class="generate__content-btn">
                            <div class="content">
                                <h5 class="h5">Unique Image Finder / Generator</h5>
                                <p>
                                    You can generate the most similar version of the image you need <a
                                        style="text-decoration: underline;">royalty-free</a> or find it by searching <a
                                        style="text-decoration: underline;">the entire internet</a>.
                                </p>
                            </div>
                        </div>
                        <div class="generate__content-btn">
                            <div class="content">
                                <h5 class="h5">Outputting - Transferring in Desired Formats</h5>
                                <p>
                                    You can output your created image in the desired format and transfer it to other
                                    ZOBOX artificial intelligence tools such as <a
                                        style="text-decoration: underline;">Presentation.ai, CV Maker</a>.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-lg-6 col-xl-7">
                    <div class="generate__thumb wow fadeInUp" data-wow-duration="600ms" data-wow-delay="300ms">
                        <div class="tab-content active">
                            <div class="rangu rangu-two">
                                <div class="img background-img"></div>
                                <div class="img foreground-img3"></div>
                                <input type="range" min="1" max="100" value="50" class="rangu-slider"
                                    name="rangu-slider3" id="ranguslider3">
                                <div class="rangu-slider-button2 rangu-slider-button4"></div>
                            </div>
                        </div>
                        <div class="tab-content">
                            <div class="rangu rangu-four">
                                <div class="img background-img"></div>
                                <div class="img foreground-img5"></div>
                                <input type="range" min="1" max="100" value="50" class="rangu-slider"
                                    name="rangu-slider5" id="ranguslider5">
                                <div class="rangu-slider-button2 rangu-slider-button6"></div>
                            </div>
                        </div>
                        <div class="tab-content">
                            <div class="rangu rangu-three">
                                <div class="img background-img"></div>
                                <div class="img foreground-img4"></div>
                                <input type="range" min="1" max="100" value="50" class="rangu-slider"
                                    name="rangu-slider4" id="ranguslider4">
                                <div class="rangu-slider-button2 rangu-slider-button5"></div>
                            </div>
                        </div>
                        <div class="tab-content">
                            <div class="rangu rangu-one">
                                <div class="img background-img"></div>
                                <div class="img foreground-img-1"></div>
                                <input type="range" min="1" max="100" value="50" class="rangu-slider"
                                    name="rangu-slider2" id="ranguslider2">
                                <div class="rangu-slider-button2 rangu-slider-button3"></div>
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
    name: "Generate",
    mounted() {
        document.querySelectorAll(".tab-content").forEach((content, index) => {
            if (index !== 0) {
                content.style.display = "none";
            }
        });

        document.querySelectorAll(".generate__content-btn").forEach((btn) => {
            btn.addEventListener("click", function () {
                // Remove the 'active' class from all tab buttons
                document.querySelectorAll(".generate__content-btn").forEach((btn) => {
                    btn.classList.remove("generate__content-btn-active");
                });

                // Hide all tab content
                document.querySelectorAll(".tab-content").forEach((content) => {
                    content.style.display = "none";
                });

                // Add the 'active' class to the clicked tab button
                this.classList.add("generate__content-btn-active");

                // Get the index of the clicked tab button
                var tabIndex = Array.from(this.parentNode.children).indexOf(this);

                // Show the corresponding tab content with fade-in animation
                document.querySelectorAll(".tab-content")[tabIndex].style.display = "block";
            });
        });

        document.getElementById("ranguslider2").addEventListener("input", function (e) {
            const sliderPos2 = e.target.value;

            document.querySelector(".foreground-img-1").style.width = `${sliderPos2}%`;
            document.querySelector(".rangu-slider-button3").style.left = `calc(${sliderPos2}% - 18px)`;
        });

        document.getElementById("ranguslider3").addEventListener("input", function (e) {
            const sliderPos3 = e.target.value;

            document.querySelector(".foreground-img3").style.width = `${sliderPos3}%`;
            document.querySelector(".rangu-slider-button4").style.left = `calc(${sliderPos3}% - 18px)`;
        });

        document.getElementById("ranguslider4").addEventListener("input", function (e) {
            const sliderPos4 = e.target.value;

            document.querySelector(".foreground-img4").style.width = `${sliderPos4}%`;
            document.querySelector(".rangu-slider-button5").style.left = `calc(${sliderPos4}% - 18px)`;
        });

        document.getElementById("ranguslider5").addEventListener("input", function (e) {
            const sliderPos5 = e.target.value;

            document.querySelector(".foreground-img5").style.width = `${sliderPos5}%`;
            document.querySelector(".rangu-slider-button6").style.left = `calc(${sliderPos5}% - 18px)`;
        });

    }
}
</script>

<style scoped>
.rangu-two .background-img {
    background-image: url('~@/assets/images/after/two-before.png');
}

.rangu-two .foreground-img3 {
    background-image: url('~@/assets/images/after/two-after.png');
}

.rangu-four .background-img {
    background-image: url('~@/assets/images/after/four-before.png');
}

.rangu-four .foreground-img5 {
    background-image: url('~@/assets/images/after/four-after.png');
}

.rangu-three .background-img {
    background-image: url('~@/assets/images/after/three-before.png');
}

.rangu-three .foreground-img4 {
    background-image: url('~@/assets/images/after/three-after.png');
}

.rangu-one .background-img {
    background-image: url('~@/assets/images/after/one-before.png');
}

.rangu-one .foreground-img-1 {
    background-image: url('~@/assets/images/after/one-after.png');
}
</style>