<template>
<div>
  <div class="container">
    <div class="flex -mx-4 mb-10">
      <div class="w-1/4 px-4 flex items-center">
        <div class="min-w-max mr-4">
          <img width="80" src="~/assets/img/customer-support.png" alt="">
        </div>
        <div class="w-full">
          <h3 class="text-xl font-medium mb-2">24 Customer Support</h3>
          Contact us 24 hours
        </div>
      </div>
      <div class="w-1/4 px-4 flex items-center">
        <div class="min-w-max mr-4">
          <img width="80" src="~/assets/img/authentic-products.png" alt="">
        </div>
        <div class="w-full">
          <h3 class="text-xl font-medium mb-2">Authentic Products</h3>
          Contact us 24 hours
        </div>
      </div>
      <div class="w-1/4 px-4 flex items-center">
        <div class="min-w-max mr-4">
          <img width="80" src="~/assets/img/secure-payment.png" alt="">
        </div>
        <div class="w-full">
          <h3 class="text-xl font-medium mb-2">Secure Payment</h3>
          Contact us 24 hours
        </div>
      </div>
      <div class="w-1/4 px-4 flex items-center">
        <div class="min-w-max mr-4">
          <img width="80" src="~/assets/img/best-price.png" alt="">
        </div>
        <div class="w-full">
          <h3 class="text-xl font-medium mb-2">Best Price and Offers</h3>
          Contact us 24 hours
        </div>
      </div>
    </div>
  </div>
  <div class="bg-gray-200 py-20">
    <div class="container">
      <div class="flex">
        <div class="w-3/5 pr-10">
          <logo/>
          <p class="my-6">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus consequuntur, ducimus eos ipsum non omnis voluptas. Blanditiis ea libero voluptatum.Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatem, voluptatibus!</p>
          <div class="flex">
            <a class="mr-4" href="" target="_blank"><img src="~/assets/img/playstore.png" alt=""></a>
            <a class="" href="" target="_blank"><img src="~/assets/img/appstore.png" alt=""></a>
          </div>
        </div>
        <div class="w-1/5 pl-6">
          <h3 class="text-2xl md-6">
            About Us
          </h3>
          <ul class="leading-loose">
            <li><nuxt-link to="/">Abouts Karte</nuxt-link></li>
            <li><nuxt-link to="/">Contact</nuxt-link></li>
            <li><nuxt-link to="/">Career</nuxt-link></li>
            <li><nuxt-link to="/">Terms & Conditions</nuxt-link></li>
            <li><nuxt-link to="/">Category</nuxt-link></li>
          </ul>
        </div>
        <div class="w-1/5 pl-6">
          <h3 class="text-2xl md-6">
            About Us
          </h3>
          <ul class="leading-loose">
            <li><nuxt-link to="/">Abouts Karte</nuxt-link></li>
            <li><nuxt-link to="/">Contact</nuxt-link></li>
            <li><nuxt-link to="/">Career</nuxt-link></li>
            <li><nuxt-link to="/">Terms & Conditions</nuxt-link></li>
            <li><nuxt-link to="/">Category</nuxt-link></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>

</style>
