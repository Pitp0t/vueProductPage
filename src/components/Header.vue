<script>
export default {
  name: "Header",
};
</script>

<template>
  <header class="header">
    <nav class="navBar">
      <img alt="Logo" class="" src="../assets/logoFoschia.jpg" height="78" /><img />
      <div class="menuitem d-none d-md-flex">
        <svg class="menuSvg" height="24" width="24" fill="white"><path d="m12 15.4-6-6L7.4 8l4.6 4.6L16.6 8 18 9.4Z" /></svg>
        <h3>Menú</h3>
      </div>
      <div class="inputGroup d-none d-md-flex">
        <input class="searchBar" placeholder="Buscar productos, marcas y mas..." type="text" />
        <div class="containerOfertaSearch">
          <div class="checkboxGroup">
            <input type="checkbox" />
            <h3>en ofertas</h3>
          </div>
          <v-btn elevation="2" class="searchButton" s-large color="primary">
            <svg class="cartSvg" height="24" width="24" fill="white">
              <path
                d="m19.6 21-6.3-6.3q-.75.6-1.725.95Q10.6 16 9.5 16q-2.725 0-4.612-1.887Q3 12.225 3 9.5q0-2.725 1.888-4.613Q6.775 3 9.5 3t4.613 1.887Q16 6.775 16 9.5q0 1.1-.35 2.075-.35.975-.95 1.725l6.3 6.3ZM9.5 14q1.875 0 3.188-1.312Q14 11.375 14 9.5q0-1.875-1.312-3.188Q11.375 5 9.5 5 7.625 5 6.312 6.312 5 7.625 5 9.5q0 1.875 1.312 3.188Q7.625 14 9.5 14Z"
              />
            </svg>
          </v-btn>
        </div>
      </div>
      <a class="contactLink d-none d-md-block" href="#">
        <h2>Atención al cliente</h2>
        <div class="contact">
          <svg class="cartSvg" height="24" width="24" fill="white">
            <path
              d="M5.85 17.1q1.275-.975 2.85-1.538Q10.275 15 12 15q1.725 0 3.3.562 1.575.563 2.85 1.538.875-1.025 1.363-2.325Q20 13.475 20 12q0-3.325-2.337-5.663Q15.325 4 12 4T6.338 6.337Q4 8.675 4 12q0 1.475.488 2.775.487 1.3 1.362 2.325ZM12 13q-1.475 0-2.488-1.012Q8.5 10.975 8.5 9.5t1.012-2.488Q10.525 6 12 6t2.488 1.012Q15.5 8.025 15.5 9.5t-1.012 2.488Q13.475 13 12 13Zm0 9q-2.075 0-3.9-.788-1.825-.787-3.175-2.137-1.35-1.35-2.137-3.175Q2 14.075 2 12t.788-3.9q.787-1.825 2.137-3.175 1.35-1.35 3.175-2.138Q9.925 2 12 2t3.9.787q1.825.788 3.175 2.138 1.35 1.35 2.137 3.175Q22 9.925 22 12t-.788 3.9q-.787 1.825-2.137 3.175-1.35 1.35-3.175 2.137Q14.075 22 12 22Zm0-2q1.325 0 2.5-.387 1.175-.388 2.15-1.113-.975-.725-2.15-1.113Q13.325 17 12 17t-2.5.387q-1.175.388-2.15 1.113.975.725 2.15 1.113Q10.675 20 12 20Zm0-9q.65 0 1.075-.425.425-.425.425-1.075 0-.65-.425-1.075Q12.65 8 12 8q-.65 0-1.075.425Q10.5 8.85 10.5 9.5q0 .65.425 1.075Q11.35 11 12 11Zm0-1.5Zm0 9Z"
            />
          </svg>
          <h3>11 6011 6413</h3>
        </div>
      </a>
      <v-btn elevation="2" class="userButton d-none d-md-block" s-large color="primary">
        <svg class="cartSvg" height="20" width="20" fill="white">
          <path
            d="M10 10q-1.25 0-2.125-.875T7 7q0-1.25.875-2.125T10 4q1.25 0 2.125.875T13 7q0 1.25-.875 2.125T10 10Zm-6 6v-2q0-.479.26-.906.261-.427.719-.719 1.146-.667 2.427-1.021Q8.688 11 10 11q1.312 0 2.594.354 1.281.354 2.427 1.021.458.271.719.708.26.438.26.917v2Zm1.5-1.5h9V14q0-.104-.062-.198-.063-.094-.167-.135-.959-.584-2.042-.875Q11.146 12.5 10 12.5q-1.146 0-2.229.292-1.083.291-2.042.875-.104.083-.167.156-.062.073-.062.177Zm4.5-6q.625 0 1.062-.438Q11.5 7.625 11.5 7t-.438-1.062Q10.625 5.5 10 5.5t-1.062.438Q8.5 6.375 8.5 7t.438 1.062Q9.375 8.5 10 8.5ZM10 7Zm0 7.5Z"
          />
        </svg>
        <h3>Ingresar</h3>
      </v-btn>
      <v-btn elevation="2" class="cartButton d-none d-md-block" s-large color="primary">
        <svg class="cartSvg" height="20" width="20" fill="white">
          <path
            d="M9.104 7.542v-2.48H6.625v-1.75h2.479V.833h1.75v2.479h2.479v1.75h-2.479v2.48ZM5.833 18.333q-.708 0-1.208-.5t-.5-1.208q0-.708.5-1.208t1.208-.5q.709 0 1.209.5.5.5.5 1.208t-.5 1.208q-.5.5-1.209.5Zm8.313 0q-.708 0-1.208-.5t-.5-1.208q0-.708.5-1.208t1.208-.5q.708 0 1.208.5t.5 1.208q0 .708-.5 1.208t-1.208.5Zm-8.334-4.125q-.937 0-1.447-.843-.511-.844-.032-1.677l1.084-2-2.959-6.271H.792v-1.75h2.77l3.563 7.479h5.792l3.187-5.834 1.542.876L14.438 10q-.23.417-.626.656-.395.24-.874.24H6.771l-.875 1.562h9.958v1.75Z"
          />
        </svg>
        <span class="numberItems">7</span>
      </v-btn>

      <!-- NAVBAR MOBILE hamburguer+ cart -->
      <div class="d-flex d-md-none mobileHeader">
        <v-btn elevation="2" class="userButton d-flex d-md-none" s-large color="primary">
          <svg class="cartSvg" height="24" width="24" fill="white"><path d="M3 18v-2h18v2Zm0-5v-2h18v2Zm0-5V6h18v2Z" /></svg>
        </v-btn>

        <v-btn elevation="2" class="cartButton" s-large color="primary">
          <svg class="cartSvg" height="20" width="20" fill="white">
            <path
              d="M9.104 7.542v-2.48H6.625v-1.75h2.479V.833h1.75v2.479h2.479v1.75h-2.479v2.48ZM5.833 18.333q-.708 0-1.208-.5t-.5-1.208q0-.708.5-1.208t1.208-.5q.709 0 1.209.5.5.5.5 1.208t-.5 1.208q-.5.5-1.209.5Zm8.313 0q-.708 0-1.208-.5t-.5-1.208q0-.708.5-1.208t1.208-.5q.708 0 1.208.5t.5 1.208q0 .708-.5 1.208t-1.208.5Zm-8.334-4.125q-.937 0-1.447-.843-.511-.844-.032-1.677l1.084-2-2.959-6.271H.792v-1.75h2.77l3.563 7.479h5.792l3.187-5.834 1.542.876L14.438 10q-.23.417-.626.656-.395.24-.874.24H6.771l-.875 1.562h9.958v1.75Z"
            />
          </svg>
          <span class="numberItems">7</span>
        </v-btn>
      </div>
    </nav>
    <!--SEARCHBAR MOBILE -->
    <div class="inputMobile d-flex d-md-none">
      <input class="searchBar" placeholder="Buscar productos, marcas y mas..." type="text" />
      <div class="containerOfertaSearch">
        <div class="checkboxGroup">
          <input type="checkbox" />
          <h3>en ofertas</h3>
        </div>
        <v-btn elevation="2" class="searchButton" s-large color="primary">
          <svg class="cartSvg" height="24" width="24" fill="white">
            <path
              d="m19.6 21-6.3-6.3q-.75.6-1.725.95Q10.6 16 9.5 16q-2.725 0-4.612-1.887Q3 12.225 3 9.5q0-2.725 1.888-4.613Q6.775 3 9.5 3t4.613 1.887Q16 6.775 16 9.5q0 1.1-.35 2.075-.35.975-.95 1.725l6.3 6.3ZM9.5 14q1.875 0 3.188-1.312Q14 11.375 14 9.5q0-1.875-1.312-3.188Q11.375 5 9.5 5 7.625 5 6.312 6.312 5 7.625 5 9.5q0 1.875 1.312 3.188Q7.625 14 9.5 14Z"
            />
          </svg>
        </v-btn>
      </div>
    </div>
  </header>
</template>

<style lang="scss">
.header {
  color: white;
  height: 78px;
  background-color: #007ac1;
  .navBar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 10px;
    .menuitem {
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .inputGroup {
      background-color: white;
      margin: 0 32px;
      padding: 0 0.2em;
      border-radius: 0.5em;
      height: 45px;
      flex-grow: 1;
      display: flex;
      align-items: center;
      justify-content: space-between;
      .searchBar {
        flex-grow: 1;
        &:focus {
          outline: none;
        }
      }
      .containerOfertaSearch {
        display: flex;
        gap: 10px;
        .searchButton {
          height: 40px;
          width: 10px;
          border-radius: 0 0.5em 0.5em 0;
        }
        .checkboxGroup {
          display: flex;
          align-items: center;
          h3 {
            color: black;
            font-weight: bold;
          }
        }
      }
    }
  }
  .contactLink {
    color: white;
    text-decoration: none;
    h2 {
      font-weight: bold;
    }
    .contact {
      display: flex;
      align-items: center;
      gap: 10px;
    }
  }
  .numberItems {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: red;
    text-align: center;
    aspect-ratio: 1;
    width: 20px;
    border-radius: 50%;
  }

  .userButton {
    h3 {
      text-transform: capitalize;
    }
  }
}
.inputMobile {
  box-shadow: 3px 17px 38px -6px rgba(99, 99, 99, 0.65);
  background-color: white;
  padding: 0 0.2em;
  border-radius: 0.5em;
  height: 45px;
  flex-grow: 1;
  display: flex;
  align-items: center;
  justify-content: space-between;
  .searchBar {
    flex-grow: 1;
    &:focus {
      outline: none;
    }
  }
  .containerOfertaSearch {
    display: flex;
    gap: 10px;
    .searchButton {
      height: 40px;
      widows: 40px;
      border-radius: 0 0.5em 0.5em 0;
    }
    .checkboxGroup {
      display: flex;
      align-items: center;
      h3 {
        color: black;
        font-weight: bold;
      }
    }
  }
}
.mobileHeader {
  gap: 10px;
}
</style>
