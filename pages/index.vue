<template>
  <div>
    <div class="p-8">
      <vue-slick-carousel class="hero-slide" :arrows="false" :dots="true">
      <div class="slide-bg rounded-2xl pt-8">
        <div class="container">
          <div class="flex items-center">
            <div class="w-1/2 mr-6 font-size-22">
            <p class="hs-dark-green-color font-size-32 mb-4">Save up 30% off</p>
            <h2 class="text-7xl font-bold md-6 text-gray-800">Bengal Vegetable farm Organic 100%</h2>
            <p class="mb-8"> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Possimus, dicta. </p>
            <nuxt-link to="/" class="hs-button text-base">Shop Now</nuxt-link>
            </div>
            <div class="w-1/2 flex justify-end ">
              <img width="550" src="~/assets/img/hero.png" alt="" >
            </div>
          </div>
        </div>
      </div>
      <div class="slide-bg rounded-2xl pt-8">
        <div class="container">
          <div class="flex">
            <div class="w-1/2 mr-6 font-size-22">
            <p class="hs-dark-green-color font-size-32 mb-4">Save up 30% off</p>
            <h2 class="text-7xl font-bold md-6 text-gray-800">Bengal Vegetable farm Organic 100%</h2>
            <p class="mb-8"> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Possimus, dicta. </p>
            <nuxt-link to="/" class="hs-button text-base">Shop Now</nuxt-link>
            </div>
            <div class="w-1/2 flex justify-end ">
              <img width="550" src="~/assets/img/hero.png" alt="" >
            </div>
          </div>
        </div>
      </div>
      <div class="slide-bg rounded-2xl pt-8">
        <div class="container">
          <div class="flex">
            <div class="w-1/2 mr-6 font-size-22">
            <p class="hs-dark-green-color font-size-32 mb-4">Save up 30% off</p>
            <h2 class="text-7xl font-bold md-6 text-gray-800">Bengal Vegetable farm Organic 100%</h2>
            <p class="mb-8"> Lorem ipsum dolor, sit amet consectetur adipisicing elit. Possimus, dicta. </p>
            <nuxt-link to="/" class="hs-button text-base">Shop Now</nuxt-link>
            </div>
            <div class="w-1/2 flex justify-end ">
              <img width="550" src="~/assets/img/hero.png" alt="" >
            </div>
          </div>
        </div>
      </div>
      </vue-slick-carousel>

      <div class="container">
        
      </div>
    </div>
  </div>
</template>

<script>
import Header from "../components/Header";
import Footer from "../components/Footer";
export default {
  name: 'IndexPage',
  components: {Header, Footer}
}
</script>
