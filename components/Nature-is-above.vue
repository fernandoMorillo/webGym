<template>
  <section class="d-flex">
    <div class="container-info-nature">
      <div class="col-lg-7">
        <h4 class="text-uppercase">nature is above all</h4>
        <p><span>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          Ab adipisci at consequuntur dolores dolorum eum facere, impedit itaque, minus neque, odio placeat quibusdam quod
          reiciendis rerum saepe soluta. In, non?</span>
        </p>
      </div>
    </div>
    <div>
      <b-img src="fondos/bg-nature.jpg"></b-img>
    </div>
  </section>
</template>

<script>
export default {
  name: "Nature-is-above"
}
</script>

<style scoped>
.container-info-nature{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.container-info-nature > div > h4 {
  color: #3ea2d8;
}

.container-info-nature > div {
  padding-top: 156px;
}

.container-info-nature > div > p {
  text-align: left;
}

</style>
