<script>
export default {
  name: "ProductInfo",
};
</script>

<template>
  <div class="productInfo_container d-flex flex-column flex-md-row justify-center">
    <div class="galery d-flex flex-column">
      <div class="d-flex galery d-flex flex-column flex-md-row justify-center">
        <div class="galery__side d-flex flex-row flex-md-column">
          <img class="galery__side_img" src="../assets/foto2.webp" alt="" />
          <img class="galery__side_img" src="../assets/foto2.webp" alt="" />
          <img class="galery__side_img" src="../assets/foto2.webp" alt="" />
          <img class="galery__side_img" src="../assets/foto2.webp" alt="" />
        </div>
        <img class="galery_side_principal" src="../assets/foto2.webp" alt="" />
      </div>
      <div class="d-none d-md-flex flex-column">
        <div class="moreInfo">
          <h2 class="subtitle mb-6">Características</h2>
          <div class="d-flex flex-row flex-md-column mr-6">
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
    </div>
    <div class="sideInfo">
      <div class="favIcon">
        <svg height="24" width="24">
          <path
            d="m12 19.65-.75-.675q-2.45-2.25-4.05-3.838-1.6-1.587-2.537-2.8-.938-1.212-1.301-2.2Q3 9.15 3 8.15q0-1.9 1.3-3.2 1.3-1.3 3.2-1.3 1.325 0 2.475.675Q11.125 5 12 6.3q.875-1.3 2.025-1.975T16.5 3.65q1.9 0 3.2 1.3 1.3 1.3 1.3 3.2 0 1-.362 1.987-.363.988-1.3 2.2-.938 1.213-2.526 2.8-1.587 1.588-4.062 3.838Zm0-1.35q2.4-2.175 3.95-3.725 1.55-1.55 2.45-2.688.9-1.137 1.25-2.012T20 8.15q0-1.5-1-2.5t-2.5-1q-1.2 0-2.212.687-1.013.688-1.788 2.038h-1Q10.7 6 9.7 5.325q-1-.675-2.2-.675-1.475 0-2.487 1Q4 6.65 4 8.15q0 .85.35 1.725.35.875 1.25 2.012.9 1.138 2.45 2.675Q9.6 16.1 12 18.3Zm0-6.825Z"
          />
        </svg>
      </div>
      <div class="shareIcon">
        <svg xmlns="http://www.w3.org/2000/svg" height="24" width="24">
          <path
            d="M18 21.5q-1.05 0-1.775-.725Q15.5 20.05 15.5 19q0-.2.038-.413.037-.212.112-.412l-7.75-4.55q-.375.4-.862.637Q6.55 14.5 6 14.5q-1.05 0-1.775-.725Q3.5 13.05 3.5 12q0-1.05.725-1.775Q4.95 9.5 6 9.5q.55 0 1.038.238.487.237.862.637l7.75-4.55q-.075-.2-.112-.413Q15.5 5.2 15.5 5q0-1.05.725-1.775Q16.95 2.5 18 2.5q1.05 0 1.775.725Q20.5 3.95 20.5 5q0 1.05-.725 1.775Q19.05 7.5 18 7.5q-.55 0-1.038-.238-.487-.237-.862-.637l-7.75 4.55q.075.2.113.412.037.213.037.413 0 .2-.037.412-.038.213-.113.413l7.75 4.55q.375-.4.862-.637Q17.45 16.5 18 16.5q1.05 0 1.775.725.725.725.725 1.775 0 1.05-.725 1.775-.725.725-1.775.725Zm0-15q.625 0 1.062-.438Q19.5 5.625 19.5 5t-.438-1.062Q18.625 3.5 18 3.5t-1.062.438Q16.5 4.375 16.5 5t.438 1.062Q17.375 6.5 18 6.5Zm-12 7q.625 0 1.062-.438Q7.5 12.625 7.5 12t-.438-1.062Q6.625 10.5 6 10.5t-1.062.438Q4.5 11.375 4.5 12t.438 1.062Q5.375 13.5 6 13.5Zm12 7q.625 0 1.062-.438.438-.437.438-1.062t-.438-1.062Q18.625 17.5 18 17.5t-1.062.438Q16.5 18.375 16.5 19t.438 1.062q.437.438 1.062.438ZM18 5ZM6 12Zm12 7Z"
          />
        </svg>
      </div>
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
      <div class="d-flex d-md-none flex-column">
        <div class="moreInfo">
          <h2 class="subtitle mb-6">Características</h2>
          <div class="d-flex flex-row flex-md-column mr-6">
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
  border-top: 1px solid #eee;
  position: relative;
  height: fit-content;
  display: flex;
  flex-direction: column;
  position: sticky;
  top: 78px;
  border-left: 1px solid #eee;
  padding: 2rem;
  gap: 1rem;
  .favIcon {
    padding: 0.5em;
    position: absolute;
    top: 15px;
    right: 15px;
  }
  .shareIcon {
    padding: 0.5em;
    position: absolute;
    top: 45px;
    right: 15px;
  }
}
.galery {
  flex-basis: 120%;
  .galery_side_principal {
    border-left: 1px solid #eee;
    height: 500px;
    width: 100%;
    object-fit: contain;
  }

  .galery__side_img {
    // max-width: 25%;
    width: 125px;

    cursor: pointer;
    object-fit: contain;
    border-bottom: 1px solid #eee;
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
  border-top: 1px solid #eee;
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

@media only screen and (max-width: 960px) {
  .galery__side_img {
    max-width: 25%;
  }
}
</style>
