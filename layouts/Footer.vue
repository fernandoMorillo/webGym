<template>
  <footer class="d-flex justify-content-center py-5">
    <div class="about col-lg-2 py-5">
      <h6 class="text-uppercase pb-2">about</h6>
      <p>
        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Alias amet atque commodi corporis,
          </span>
      </p>
      <ul class="redes-sociales">
        <li>
          <nuxt-link to="">
            Facebook
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="">
            Instagram
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="">
            Twitter
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="">
            Youtube
          </nuxt-link>
        </li>
      </ul>
    </div>
    <div class="links col-lg-6">

    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>

footer {
  background-color: rgb(31, 29, 29);
  border-bottom: 20px  solid #3ea2d8;
}
.redes-sociales {
  display: flex;
  justify-content: space-evenly;
}
.about > p {
  text-align: initial !important;
  font-size: 1rem;
  font-weight: 100;
}
.about > h6 {
  font-size: 1.5rem;
  color: rgb(255, 255, 255);
}
</style>
