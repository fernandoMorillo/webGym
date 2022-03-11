<template>
  <section class="py-5">
    <div class="container-cards">
      <div class="container-info">
        <h2 class="text-uppercase mb-4">we use less water</h2>
        <p class="mt-3">
        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusantium aut commodi consequatur cum
          ducimus est fugit ipsa itaque laboriosam.</span>
        </p>
      </div>
      <div class="container-info">
        <h2 class="text-uppercase mb-4">we respect nature</h2>
        <p class="mt-3">
        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusantium aut commodi consequatur cum
          ducimus est fugit ipsa itaque laboriosam.</span>
        </p>
      </div>
      <div class="container-info">
        <h2 class="text-uppercase mb-4">we believe in recycling </h2>
        <p class="mt-3">
        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A accusantium aut commodi consequatur cum
          ducimus est fugit ipsa itaque laboriosam.</span>
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "We-use"
}
</script>

<style scoped>
section {
  background-color: rgb(31, 29, 29);
}
.container-cards {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 300px;
}

div > h2 {
  font-size: 1.5rem;
  font-weight: 900;
  color: rgb(259, 259, 259);
  width: 360px;
}

.container-info {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 508px;
}

.container-info > p {
  width: 360px;
  text-align: left;
  font-size: 1rem;
}
</style>
