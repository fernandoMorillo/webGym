<template>
  <section class="py-5">
    <div class="container py-5">
      <h3 class="text-center text-uppercase"> what exactly do we do</h3>
      <p>
      <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium asperiores aspernatur consequuntur
        cupiditate esse et impedit iusto nisi tempora, voluptates? Atque, consectetur cupiditate iure laboriosam maxime molestiae quia quo sit?</span>
      </p>
    </div>
    <div class="mt-4 pt-5 pb-5 mb-5 d-flex container-car-do-we">
      <div class="text-center card-do-we">
        <b-img src="iconos/w-sport-1.png"></b-img>
        <h4 class="text-center font-weight-bold py-3 mt-1">Sport</h4>
        <p>
          <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque consequatur cupiditate
            delectus doloremque ea enim error</span>
        </p>
      </div>
      <div class="text-center card-do-we">
        <b-img src="iconos/w-sport-2.png"></b-img>
        <h4 class="text-center font-weight-bold py-3 mt-1">Sport</h4>
        <p>
          <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque consequatur cupiditate
            delectus doloremque ea enim error</span>
        </p>
      </div>
      <div class="text-center card-do-we">
        <b-img src="iconos/w-sport-3.png"></b-img>
        <h4 class="text-center font-weight-bold py-3 mt-1">Sport</h4>
        <p>
          <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque consequatur cupiditate
            delectus doloremque ea enim error</span>
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Exactly-do-we-do"
}
</script>

<style scoped>
div > h3 {
  color: #3ea2d8;
  font-weight: 900;
  font-size: 1.7rem;
}

div > p {
  color: #3ea2d8;
  font-size: 1.2rem;
}

.card-do-we {
  margin: 14px;
  width: 278px;
}

.container-car-do-we {
  justify-content: space-evenly;
}

div > h4 {
  color: rgb(255, 255, 255);
}
</style>
