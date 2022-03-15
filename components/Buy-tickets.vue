<template>
  <section class="background-buy">
    <div class="container-superior">
      <div class="col-lg-3 container-buy">
        <h4 class="text-uppercase font-weight-bold">Buy your Tickets</h4>
        <p>
        <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. A eum iste magnam placeat quidem quisquam
          uscipit voluptate? Architecto delectus, dignissimos doloremque doloribus dolorum eaque ipsa ipsam repudiandae tenetur voluptate. Enim?</span>
        </p>
        <b-button class="text-uppercase btn-buy-here">here</b-button>
      </div>
    </div>

  </section>
</template>

<script>
export default {
  name: "Buy-tickets"
}
</script>

<style scoped>
.background-buy {
  background-image: url("/fondos/bg-buy.jpg");
  height: 100vh;
  background-size: cover;
}
.container-superior {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  height: 100vh;
  margin-right: 231px;
}
.container-buy{
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-end;
}

.container-buy > h4 {
  font-size: 3rem;
  text-align: end;
  color: rgb(255, 255, 255);
}
.container-buy > p {
  text-align: right;
}

.btn-buy-here {
  background-color: white;
  color: #3ea2d8;
  border-radius: 150px;
  width: 149px;
}
</style>
