<template>
  <div class="flex flex-col w-screen p-8">
    <product-headline>
      <template v-slot:product-image>
        <img class="h-full w-full object-cover" src="https://cf.shopee.com.my/file/82950df9faa19d4d1a5215976e1be601" alt="">
      </template>
      <template v-slot:product-title>
        Brazil Santa Lucia (Natural) - Single Origin Espresso Roast Coffee Beans
      </template>
      <template v-slot:product-weight>
        <div class="py-2 px-4 border border-gray-200 mx-2 cursor-pointer hover:border-orange-600 hover:text-orange-600 transition-all duration-300 ease-in-out">200g</div>
        <div class="py-2 px-4 border border-gray-200 mx-2 cursor-pointer hover:border-orange-600 hover:text-orange-600 transition-all duration-300 ease-in-out">500g</div>
      </template>
      <template v-slot:product-category>
        <div class="py-1 px-2 border border-gray-200 mx-2 cursor-pointer hover:border-orange-600 hover:text-orange-600 transition-all duration-300 ease-in-out">Whole Bean</div>
        <div class="py-1 px-2 border border-gray-200 mx-2 cursor-pointer hover:border-orange-600 hover:text-orange-600 transition-all duration-300 ease-in-out">Espresso Grind</div>
        <div class="py-1 px-2 border border-gray-200 mx-2 cursor-pointer hover:border-orange-600 hover:text-orange-600 transition-all duration-300 ease-in-out">Moka Pot Grind</div>
        <div class="py-1 px-2 border border-gray-200 mx-2 cursor-pointer hover:border-orange-600 hover:text-orange-600 transition-all duration-300 ease-in-out">French Press</div>
      </template>
    </product-headline>
  </div>
</template>

<script>
import productHeadline from '../components/product-headline.vue'
export default {
  components: { productHeadline },
}
</script>
