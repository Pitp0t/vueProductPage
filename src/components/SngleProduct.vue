<script>
export default {
  name: "SingleProduct",
};
</script>

<template>
  <div class="product">
    <div class="product_top">
      <img class="product_img" src="../assets/fotoPrueba.webp" alt="" />
      <div class="product_favIcon">
        <svg height="24" width="24">
          <path
            d="m12 19.65-.75-.675q-2.45-2.25-4.05-3.838-1.6-1.587-2.537-2.8-.938-1.212-1.301-2.2Q3 9.15 3 8.15q0-1.9 1.3-3.2 1.3-1.3 3.2-1.3 1.325 0 2.475.675Q11.125 5 12 6.3q.875-1.3 2.025-1.975T16.5 3.65q1.9 0 3.2 1.3 1.3 1.3 1.3 3.2 0 1-.362 1.987-.363.988-1.3 2.2-.938 1.213-2.526 2.8-1.587 1.588-4.062 3.838Zm0-1.35q2.4-2.175 3.95-3.725 1.55-1.55 2.45-2.688.9-1.137 1.25-2.012T20 8.15q0-1.5-1-2.5t-2.5-1q-1.2 0-2.212.687-1.013.688-1.788 2.038h-1Q10.7 6 9.7 5.325q-1-.675-2.2-.675-1.475 0-2.487 1Q4 6.65 4 8.15q0 .85.35 1.725.35.875 1.25 2.012.9 1.138 2.45 2.675Q9.6 16.1 12 18.3Zm0-6.825Z"
          />
        </svg>
      </div>
    </div>
    <div class="product_content">
      <h2 class="product_oldPrice">$79.891</h2>
      <div class="product_info">
        <div class="product_price">
          <span class="price">$47.935</span>
          <span class="offer">40% OFF</span>
        </div>

        <h3 class="product_cuotas">hasta 18 cuotas</h3>
      </div>
      <h2>Griferia Monocomando Cocina Tactil Fv Libby 411.04/39E</h2>
    </div>
    <div class="mobile">
      <button class="cartButton">
        <svg class="cartSvg" height="20" width="20">
          <path
            d="M9.104 7.542v-2.48H6.625v-1.75h2.479V.833h1.75v2.479h2.479v1.75h-2.479v2.48ZM5.833 18.333q-.708 0-1.208-.5t-.5-1.208q0-.708.5-1.208t1.208-.5q.709 0 1.209.5.5.5.5 1.208t-.5 1.208q-.5.5-1.209.5Zm8.313 0q-.708 0-1.208-.5t-.5-1.208q0-.708.5-1.208t1.208-.5q.708 0 1.208.5t.5 1.208q0 .708-.5 1.208t-1.208.5Zm-8.334-4.125q-.937 0-1.447-.843-.511-.844-.032-1.677l1.084-2-2.959-6.271H.792v-1.75h2.77l3.563 7.479h5.792l3.187-5.834 1.542.876L14.438 10q-.23.417-.626.656-.395.24-.874.24H6.771l-.875 1.562h9.958v1.75Z"
          />
        </svg>
        <h3>Comprar</h3>
      </button>
    </div>
  </div>
</template>

<style scoped lang="scss">
.product {
  position: relative;
  cursor: pointer;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding: 1em;
  gap: 1.5rem;
  background-color: white;
  box-shadow: 0 1px 1px 0 rgb(0 0 0 / 10%), 0 -1px 2px 0 rgb(0 0 0 / 10%);
  border-radius: 0.2rem;
  .product_top {
    border-bottom: 1px solid rgb(242, 242, 242);
    .product_img {
      aspect-ratio: 1;
      width: 100%;
      object-fit: contain;
    }
    .product_favIcon {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 40px;
      width: 40px;
      background-color: #f2f2f2;
      border-radius: 50%;
      position: absolute;
      top: 5px;
      right: 5px;
    }
  }
  .product_content {
    padding: 0 1em;
  }

  .product_oldPrice {
    text-decoration: line-through;
  }
  .product_cuotas {
    color: #007ac1;
  }

  .product_info {
    display: flex;
    flex-direction: column;
    gap: 10px;
    .product_price {
      display: flex;
      align-items: center;
      gap: 10px;
      .price {
        font-size: 1.5rem;
      }
      .offer {
        color: #35a3a8;
      }
    }
  }

  .cartButton {
    display: flex;
    justify-content: center;
    background-color: #f2f2f2;
    padding: 0.5em 3em;
    border-radius: 1rem;
    &:hover {
      background-color: #007ac1;
      color: white;
      .cartSvg {
        fill: "white";
      }
    }
    &:hover {
      transition: box-shadow 0.5s;
      box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.063), 0 -1px 2px 0 rgba(0, 0, 0, 0.085);
    }
  }
}

@media only screen and (max-width: 600px) {
  .mobile {
    display: none;
  }
}
</style>
