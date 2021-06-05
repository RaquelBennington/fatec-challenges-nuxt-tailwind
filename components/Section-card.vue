<template>
  <div
    class="flex items-center w-screen min-h-screen bg-white"
    style="font-family: 'Muli', sans-serif"
  >
    <div class="container ml-auto mr-auto flex flex-wrap items-start py-6">
    <Card
      v-for="product of products"
      :key="product.id"
      :photo="product.photo"
      :icon="product.icon"
      :legend="product.legend"
    />
  </div>
  </div>
</template>

<script>
import { mapState } from "vuex";
export default {
  name: "Section-card",
  computed: {
    ...mapState({
      products: (state) => state.cards.info,
    }),
  },
};
</script>
