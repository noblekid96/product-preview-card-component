<template>
  <div class="card">
    <div class="half">
      <img src="@/assets/images/image-product-desktop.jpg"/>
    </div >
    <div class="half">
      <div class="content">
        <div class="category">
          PERFUME
        </div>
        <div class="name">
          <h1>
            Gabrielle Essence Eau De Parfum
          </h1>
        </div>
        <div class="description">
          <p>
            A floral, solar and voluptuous interpretation composed by Olivier Polge,
            Perfumer-Creator for the House of CHANEL.
          </p>
        </div>
        <div class="prices">
          <span class="sale-price">
              $149.99
          </span>
          <span class="original-price">
              $169.99
          </span>
        </div>
        <div class="action">
          <button>
            <i class="fa-solid fa-cart-shopping"></i>
            Add to Cart
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
 .card {
  display: flex;
  width: 600px;
   box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
   transition: 0.3s;
   border-radius: 20px;
   background-color: hsl(0, 0%, 100%);
 }

 h1 {
   font-family: "Fraunces", serif;
   color: hsl(212, 21%, 14%);
   font-size: 2rem;
   margin-top: 25px;
   margin-bottom: 25px;
 }

 .half {
   flex: 50%;
 }

 img {
   border-radius: 20px 0px 0px 20px;
   width: 100%;
   height: 100%;
 }

 .content {
   padding: 30px;
 }

 .category {
   font-family: 'Montserrat';
   color: gray;
   text-transform: uppercase;
   letter-spacing: 4px;
 }

 .name {
   font-family: "Fraunces", serif;
   color: hsl(212, 21%, 14%);
   font-weight: 700;
 }

 .description {
   font-family: "Montserrat", sans-serif;
   color: hsl(228, 12%, 48%);
   font-size: 14px;
   font-weight: 300;
 }

 .prices {
    display: flex;
    align-items: center;
    margin-top: 40px;
    margin-bottom: 40px;
 }

 .sale-price {
    font-family: "Fraunces", serif;
    color:hsl(158, 36%, 37%);
    font-size: 1.7rem;
    margin-right: 20px;
 }

 .original-price {
    text-decoration: line-through;
   color: hsl(228, 12%, 48%);
 }

button {
    font-family: "Montserrat", sans-serif;
    font-weight: 700;
    background-color: hsl(158, 36%, 37%);
    color: hsl(0, 0%, 100%);
    padding: 20px;
    border-style: none;
    border-radius: 10px;
    height: 50px;
    width: 100%;
}

button:hover {
    background-color: hsl(158, 45%, 20%);
}

button:active {
    background-color: hsl(158, 45%, 20%);
}

.fa-cart-shopping {
    margin-right: 10px;
}


</style>
