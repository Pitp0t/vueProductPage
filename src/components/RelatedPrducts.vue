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
  <div class="relatedContent">
    <h2 class="titleRelated">También te puede interesar</h2>
    <v-container class="relatedContainer">
      <SingleProduct />
      <SingleProduct />
      <SingleProduct />
      <SingleProduct />
    </v-container>
  </div>
</template>

<style scoped lang="scss">
.relatedContainer {
  padding: 0;

  margin: 0;
  display: grid;
  place-content: center;
  gap: 10px;
  grid-template-columns: repeat(4, minmax(250px, 1fr));
}
.relatedContent {
  margin: 10em auto;
  max-width: 1200px;
}
.titleRelated {
  margin-bottom: 1rem;
  border-bottom: 1px solid rgba(128, 128, 128, 0.103);
  text-align: left;
  font-size: 1.5rem;
  font-weight: bold;
}

@media only screen and (max-width: 960px) {
  .relatedContent {
    padding: 0 1em;
  }
  .relatedContainer {
    grid-template-columns: repeat(2, minmax(100px, 1fr));
  }
}
</style>
