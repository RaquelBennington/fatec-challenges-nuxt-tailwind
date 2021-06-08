<template>
  <div class="w-full md:w-1/2 lg:w-1/4 pl-5 pr-5 mb-5 lg:pl-2 lg:pr-2">
    <div
      class="bg-pink rounded m-h-64 p-2 border-black border border-t border-b border-r"
    >
      <figure class="mb-2 py-2">
        <img :src="photo" :alt="legend" class="h-64 ml-auto mr-auto" />
      </figure>

      <div class="rounded-lg bg-white flex justify-between">
        <div class="flex mx-2 sm:mx-6">
          <a href="items-center" target="_blank"><Icon/></a>
          <p class="text-base text-gray-600 leading-none">{{ legend }}</p>
          
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Card",

  props: {
    photo: {
      type: String,
      default: "",
    },

    icon: {
      type: String,
      default: "",
    },

    legend: {
      type: String,
      default: "",
    },
  },
};
</script>
