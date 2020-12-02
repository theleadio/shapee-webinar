<template>
  <content-card class="font-poppins">
      <template v-slot:content>
        <div class="grid grid-cols-1 md:grid-cols-5 gap-2">
          <div class="col-span-2">
            <slot name="product-image"></slot>
          </div>
          <div class="col-span-3">
            <div class="flex flex-col px-4 py-2">
                <div class="text-lg md:text-xl font-medium">
                    <slot name="product-title"></slot>
                </div>
                <div class="text-sm font-light text-gray-600">
                    <div class="flex items-center justify-start py-2">
                        <div>
                            No Ratings Yet
                        </div>
                        <div class="mx-4 text-gray-400 text-lg">
                            |
                        </div>
                        <div>
                            0 Sold
                        </div>
                    </div>
                </div>
                <div class="flex flex-col pl-12 py-4">
                    <div class="text-3xl font-medium text-orange-600 py-2">
                        RM 50.00
                    </div>
                    <div class="text-gray-600 text-sm py-2 grid grid-cols-4 gap-2">
                        <div class="px-3">
                            Shipping
                        </div>
                        <div class="flex flex-col col-span-3">
                            <div class='flex items-center justify-start'>
                                <div class="px-2">
                                    Shipping To
                                </div>
                                <div class="px-4">
                                    Kuala Lumpur
                                </div>
                            </div>
                            <div class='flex items-center justify-start'>
                                <div class="px-2">
                                    Shipping Fee
                                </div>
                                <div class="px-4">
                                    RM8.00
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="flex text-gray-600 text-sm py-2 items-center grid grid-cols-4 gap-2">
                        <div class="px-3">
                            Weight
                        </div>
                        <div class="grid grid-cols-2 md:grid-cols-3 col-span-3 text-center">
                            <slot name="product-weight"></slot>
                        </div>
                    </div>
                    <div class="text-gray-600 text-sm py-2 items-center grid grid-cols-4 gap-2">
                        <div class="px-3">
                            Select Grind
                        </div>
                        <div class="grid grid-cols-2 md:grid-cols-3 gap-1 text-xs lg:text-sm col-span-3 text-center">
                            <slot name="product-category"></slot>
                        </div>
                    </div>
                    <div class="flex text-gray-600 text-sm py-2 items-center">
                        <button type="button" class="py-4 px-8 mx-4 bg-orange-200 border border-orange-600 text-orange-600  transition-all duration-300 ease-in-out hover:bg-orange-300">
                            Add To Cart
                        </button>
                        <button type="button" class="py-4 px-10 bg-orange-600 text-white mx-4 hover:bg-orange-500 transition-all duration-300 ease-in-out">
                            Buy Now
                        </button>
                    </div>
                </div>
            </div>
          </div>
        </div>
      </template>
    </content-card>
</template>

<script>
export default {

}
</script>

<style>

</style>