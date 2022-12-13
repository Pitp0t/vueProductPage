<script>
import SingleProduct from "../components/SngleProduct.vue";
export default {
  name: "RelatedProducts",
  components: {
    SingleProduct,
  },
};
</script>

<template>
  <div class="relatedContainer">
    <SingleProduct />
    <SingleProduct />
    <SingleProduct />
    <SingleProduct />
  </div>
</template>

<style scoped lang="scss">
.relatedContainer {
  display: grid;
  place-content: center;
  margin: 10em auto;
  max-width: 1200px;
  gap: 1rem;
  grid-template-columns: repeat(4, minmax(5%, 1fr));
}
</style>
