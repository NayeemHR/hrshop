<template>
  <div>
    <div class="container">
      <div class="py-6 flex justify-between items-center">
        <logo/>

        <div class="w-96">
          <div class=" border border-gray-100 p-1 flex rounded-full items-center">
            <div class="min-w-max px-3">
              <img src="~/assets/img/search.png" alt="">
            </div>
            <input class="w-full px-3 pxy-1 focus:outline-none"  type="search" placeholder="Search Here...">
            <button class="bg-gray hs-button-bg px-6 rounded-full py-2 text-white" type="submit">Search</button>
          </div>
        </div>
        <div class="min-w-max flex items-center">
          <input-link to="/" ><span class="hs-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/fav.png" alt=""></span></input-link>
          <input-link to="/" class="relative mx-4"><span class="hs-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/cart.png" alt=""></span><span class="absolute bg-red-600 w-4 h-4 top-0 right-0 rounded-full text-xs flex items-center justify-center text-white">8</span></input-link>
          <input-link to="/" class="flex items-center"><span class="hs-icon-box rounded-full hover:bg-gray-200 inline-block flex items-center justify-center"><img src="~/assets/img/user.png" alt=""></span><span>Account</span></input-link>

        </div>
      </div>

      <div class="flex">
        <div class="w-96 items-center">
          <div class="hs-dark-green-bg flex rounded-full px-4 py-2 cursor-pointer ">
            <div class="min-w-max">
              <img src="~/assets/img/menu-right.png" alt="">
            </div>
            <div class="w-full text-center px-6 text-white">
              All Categories
            </div>
            <div class="min-w-max">
              <img src="~/assets/img/chevron-down.png" alt="">
            </div>
          </div>
        </div>
        <div class="w-full">
          <ul class="flex justify-center">
            <li><nuxt-link class="p-4" to="/">Home</nuxt-link></li>
            <li><nuxt-link class="p-4" to="/">Categories</nuxt-link></li>
            <li><nuxt-link class="p-4" to="/">About</nuxt-link></li>
            <li><nuxt-link class="p-4" to="/">Contact</nuxt-link></li>
            <li><nuxt-link class="p-4" to="/">FAQ</nuxt-link></li>
            <li><nuxt-link class="p-4" to="/">Offers</nuxt-link></li>
          </ul>
        </div>
        <nuxt-link to="/" class="min-w-max hs-dark-orange-color flex">
          <img src="~/assets/img/percent.png" alt="" class="mr-3"> Special Offers!
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>
