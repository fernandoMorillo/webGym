<template>
  <b-dd-header >
    <div class="confi-header">
      <div>
        <b-img src="logo/logo-fitnessgym.png"></b-img>
      </div>
      <div></div>
      <div class="menu">
        <ul>
          <li>HOME</li>
          <li>ABOUT</li>
          <li>SHOP</li>
          <li>CONTACT</li>
        </ul>
      </div>
    </div>
  </b-dd-header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
.confi-header {
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 14px;
  background-color: rgb(0, 0, 0, 100%);
}
.dropdown-header {
  padding: 0 !important;
}
.menu {
   width: 400px;
}
ul {
  display: flex;
  justify-content: space-around;
  align-items: center;
  margin-bottom: 0 !important;
  list-style: none;
  color: #3ea2d8;
}
</style>
