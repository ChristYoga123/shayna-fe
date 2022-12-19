<template>
    <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-item" :items-to-show="1" :wrap-around="true">
            <slide v-for="slide in 1" :key="slide">
                <div class="single-hero-items set-bg" style="background-image: url('/img/hero-1.jpg')">
                    <div class="container">
                        <div class="row banner-info">
                            <div class="col-lg-5">
                                <span>Bag,kids</span>
                                <h1>Black friday</h1>
                                <p>
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                                </p>
                                <a href="#" class="primary-btn">Shop Now</a>
                            </div>
                        </div>
                    </div>
                </div>
            </slide>
            <navigation />
            <pagination />
        </carousel>
    </section>
    <!-- Hero Section End -->
</template>

<script>
import "vue3-carousel/dist/carousel.css";
import {Carousel, Slide, Pagination, Navigation} from "vue3-carousel";
export default {
    name: "HeroShayna",
    components: {
        Carousel,
        Slide,
        Pagination,
        Navigation
    }
}
</script>

<style>
.set-bg{
    width: 100%;
    height: 650vh;
}

.banner-info {
    margin-top: 160px;
}
</style>