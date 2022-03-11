<template>
  <section class="container">
    <div>
      <h1 class="text-uppercase mb-4">Who Are we</h1>
    </div>
    <div>
      <p class="text-complement">
        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur blanditiis consectetur consequatur
          cum doloribus ducimus eos, error iusto, libero magni maiores natus nisi odio officiis perferendis provident quia totam, ut!</span>
        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur blanditiis consectetur consequatur
          cum doloribus ducimus eos, error iusto, libero magni maiores natus nisi odio officiis perferendis provident quia totam, ut!</span>
      </p>
    </div>
  </section>
</template>

<script>
export default {
  name: "who-are-we"
}
</script>

<style scoped>
div > h1 {
  text-align: center;
  color: #3ea2d8;
  font-size: 1.7rem;
}

div > .text-complement {
  color: #3ea2d8;
  font-size: 1rem;
}

section {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 500px;
}
</style>
