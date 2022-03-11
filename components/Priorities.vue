<template>
  <div>
    <div class="container py-5">
      <h3 class="text-uppercase text-center pt-5 pb-2"> priorities go first</h3>
      <div class="py-3">
        <p>
        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          Amet beatae ea hic illum itaque iure magnam nisi possimus soluta! Aliquam aliquid dolores facilis fuga hic illum maxime non pariatur sunt.</span>
        </p>
      </div>
    </div>
    <div class="d-flex container-cards pt-5">
      <div class="d-flex align-content-center">
        <div class="card">
          <h4 class="text-uppercase text-center pb-2">company</h4>
          <p class="infoAdmin py-3">
            <span>"Lorem ipsum dolor sit amet, consectetur adipisicing elit sed do."</span>
          </p>
          <cite class="text-center pt-3">
            Adams Jhons
            Account Manager
          </cite>
        </div>
        <div class="card">
          <h4 class="text-uppercase text-center pb-2">company</h4>
          <p class="infoAdmin py-3">
            <span>"Lorem ipsum dolor sit amet, consectetur adipisicing elit sed do."</span>
          </p>
          <cite class="text-center pt-3">
            Adams Jhons
            Account Manager
          </cite>
        </div>
        <div class="card">
          <h4 class="text-uppercase text-center pb-2">company</h4>
          <p class="infoAdmin py-3">
            <span>"Lorem ipsum dolor sit amet, consectetur adipisicing elit sed do."</span>
          </p>
          <cite class="text-center pt-3">
            Adams Jhons
            Account Manager
          </cite>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Priorities"
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

div > .infoAdmin {
  width: 317px;
}

.container-cards {
  justify-content: space-around;
  padding-bottom: 400px;
}

.card {
  padding: 50px;
  margin: 21px;
  background-color: #262626b3;
  border: none;
  height: 356px;
  display: flex;
  justify-content: center;
  color: rgb(259, 259, 259);
}

.card > h4 {
  color: rgb(259, 259, 259);
}
</style>
