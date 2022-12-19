<template>
    <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-item" :items-to-show="1" :wrap-around="true">
            <slide v-for="slide in 1" :key="slide">
                <div class="product-item">
                    <div class="pi-pic">
                        <img src="img/mickey1.jpg" alt="" />
                        <ul>
                            <li class="w-icon active">
                                <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                            </li>
                            <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                        </ul>
                    </div>
                    <div class="pi-text">
                        <div class="catagory-name">Coat</div>
                            <router-link to="/product">
                                <h5>Mickey Baggy</h5>
                            </router-link>
                        <div class="product-price">
                            $14.00
                            <span>$35.00</span>
                        </div>
                    </div>
                </div>

                <div class="product-item">
                    <div class="pi-pic">
                        <img src="img/mickey1.jpg" alt="" />
                        <ul>
                            <li class="w-icon active">
                                <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                            </li>
                            <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                        </ul>
                    </div>
                    <div class="pi-text">
                        <div class="catagory-name">Coat</div>
                            <router-link to="/product">
                                <h5>Mickey Baggy</h5>
                            </router-link>
                        <div class="product-price">
                            $14.00
                            <span>$35.00</span>
                        </div>
                    </div>
                </div>

                <div class="product-item">
                    <div class="pi-pic">
                        <img src="img/mickey1.jpg" alt="" />
                        <ul>
                            <li class="w-icon active">
                                <router-link to="/product"><i class="icon_bag_alt"></i></router-link>
                            </li>
                            <li class="quick-view"><router-link to="/product">+ Quick View</router-link></li>
                        </ul>
                    </div>
                    <div class="pi-text">
                        <div class="catagory-name">Coat</div>
                            <router-link to="/product">
                                <h5>Mickey Baggy</h5>
                            </router-link>
                        <div class="product-price">
                            $14.00
                            <span>$35.00</span>
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
    name: "WomanHeroShayna",
    components: {
        Carousel,
        Slide,
        Pagination,
        Navigation
    }
}
</script>

<style>
.product-item {
    margin-top: 20px;
    margin-right: 25px;
}

.pi-pic img {
    height: 500px;
}
</style>