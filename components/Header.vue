<template>
  <div>
    <div class="container">
      <div class="py-6 flex justify-between items-center">
        <nuxt-link to="/" class="flex font-size-32 font-medium items-center">
          <img class="mr-3" src="~/assets/img/logo.png" alt="">HRSHOP
        </nuxt-link>

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
