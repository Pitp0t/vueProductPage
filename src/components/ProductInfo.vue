<script>
export default {
  name: "ProductInfo",
};
</script>

<template>
  <div class="productInfo_container d-flex flex-column flex-md-row justify-center">
    <div class="d-flex flex-column">
      <div class="d-flex galery d-flex flex-column flex-md-row justify-center">
        <div class="galery__side d-flex flex-row flex-md-column">
          <img class="galery__side_img" src="../assets/foto2.webp" alt="" />
          <img class="galery__side_img" src="../assets/foto2.webp" alt="" />
          <img class="galery__side_img" src="../assets/foto2.webp" alt="" />
          <img class="galery__side_img" src="../assets/foto2.webp" alt="" />
        </div>
        <img class="galery_side_principal" src="../assets/foto2.webp" alt="" />
      </div>
      <div class="moreInfo">
        <h2 class="subtitle mb-6">Características</h2>
        <div class="d-flex flex-row flex-md-column">
          <div class="d-flex justify-space-between flex-column flex-md-row mb-6">
            <div>
              <h3>TIPO DE LIMPIEZA</h3>
              <h4>No utilizar abrasivos</h4>
            </div>
            <div>
              <h3>GARANTÍA</h3>
              <h4>5 años</h4>
            </div>
            <div>
              <h3>MARCA</h3>
              <h4>Ultragrif</h4>
            </div>
            <div>
              <h3>LÍNEA</h3>
              <h4>Jack</h4>
            </div>
          </div>

          <div class="d-flex justify-space-between flex-column flex-md-row">
            <div>
              <h3>CON SALIDA</h3>
              <h4>De mesada</h4>
            </div>
            <div>
              <h3>CUADRO DE DUCHA</h3>
              <h4>Monocomando</h4>
            </div>
            <div>
              <h3>TIPO DE INSTALACIÓN</h3>
              <h4>Movil</h4>
            </div>
            <div>
              <h3>IMPERMEABLE</h3>
              <h4>Argentina</h4>
            </div>
          </div>
        </div>
      </div>
      <div class="moreInfo">
        <h2 class="subtitle mb-6">Más información</h2>
        <div class="mb-6">
          <h3>DESCRIPCIÓN MARCA</h3>
          <h4>ULTRAGRIF es una empresa Argentina con amplia experiencia y trayectoria. dedicada a la comercialización de griferías.</h4>
        </div>
        <div>
          <h3>TIPO DE PINTURA</h3>
          <h4>Apto para calefon y/o termotanque</h4>
        </div>
      </div>
    </div>
    <div class="sideInfo">
      <div class="breadcrums">
        <a href="">Griferías</a>> <a href="">Griferías Para Cocina</a>>
        <a href=""> Monocomando</a>
      </div>
      <div class="product_content">
        <h2 class="product__title">Griferia De Cocina Ultragrif Jack Steel Monocomando</h2>
        <h3 class="product_oldPrice">$79.891</h3>
        <div class="product_info">
          <div class="product_price">
            <span class="price">$ 47.935</span>
            <span class="offer">40% OFF</span>
          </div>
          <span>Stock disponible</span>
          <span>Planes ahora 3, 6, 12 y 18</span>
          <span> Disponible para <a href="">Acopio en depósito</a></span>
        </div>
      </div>
      <div class="buttonInfo">
        <div class="d-flex buttonContainer">
          <button>-</button>
          <input type="number" class="control quantity" value="1" min="1" max="71" />
          <button>+</button>
        </div>
        <div>
          <h3>71 disponibles</h3>
        </div>
        <button class="buttonBuy">
          <svg class="cartSvg" height="20" width="20" fill="white">
            <path
              d="M9.104 7.542v-2.48H6.625v-1.75h2.479V.833h1.75v2.479h2.479v1.75h-2.479v2.48ZM5.833 18.333q-.708 0-1.208-.5t-.5-1.208q0-.708.5-1.208t1.208-.5q.709 0 1.209.5.5.5.5 1.208t-.5 1.208q-.5.5-1.209.5Zm8.313 0q-.708 0-1.208-.5t-.5-1.208q0-.708.5-1.208t1.208-.5q.708 0 1.208.5t.5 1.208q0 .708-.5 1.208t-1.208.5Zm-8.334-4.125q-.937 0-1.447-.843-.511-.844-.032-1.677l1.084-2-2.959-6.271H.792v-1.75h2.77l3.563 7.479h5.792l3.187-5.834 1.542.876L14.438 10q-.23.417-.626.656-.395.24-.874.24H6.771l-.875 1.562h9.958v1.75Z"
            />
          </svg>
          <h3>Comprar ahora</h3>
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.productInfo_container {
  position: relative;
  background-color: white;
  margin: 12em auto;
  max-width: 1200px;
}
.sideInfo {
  height: fit-content;
  display: flex;
  flex-direction: column;
  min-width: 300px;
  width: 400px;
  position: sticky;
  top: 78px;
  border-left: 1px solid #eee;
  padding: 2rem;
  gap: 1rem;
}
.galery {
  height: 500px;
  .galery_side_principal {
    border-left: 1px solid #eee;
    height: 500px;
    aspect-ratio: 4/3;
    width: 100%;
    object-fit: contain;
  }
  .galery__side_img {
    cursor: pointer;
    object-fit: contain;
    border-bottom: 1px solid #eee;
    width: 125px;
    aspect-ratio: 1;
    &:hover {
      border-left: 3px solid #007ac1;
    }
  }
}
.product__title {
  font-size: 1.5rem;
  line-height: 1.5rem;
}

.product_oldPrice {
  text-decoration: line-through;
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
      font-size: 2rem;
    }
    .offer {
      font-size: 0.9rem;
      color: #35a3a8;
    }
  }
}

.buttonInfo {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 10px;
}
.buttonContainer {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 20px;
  button {
    color: #007ac1;
    font-size: 2rem;
    border: 1px dotted #007ac1;
    border-radius: 0.2em;
    padding: 0 0.8rem;

    &:hover {
      background-color: #007ac1;
      color: white;
    }
  }

  input {
    width: 50px;
    outline: none;
    font-size: 1.5rem;
    text-align: center;
    border-bottom: 1px solid #eee;
  }
}

.moreInfo {
  padding: 2em;

  h3 {
    color: #007ac1;
    font-weight: bold;
  }
  h4 {
    font-size: 1rem;
  }
  .subtitle {
    font-size: 1.5rem;
    font-weight: bold;
  }
}

.buttonBuy {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
  background-color: #007ac1;
  color: white;
  padding: 0.8em 1em;
  border-radius: 0.2em;
  h3 {
    font-size: 0.9rem;
  }
}
</style>
