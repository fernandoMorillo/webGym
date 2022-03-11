<template>
  <div class="webmain">
    <div class="fondo-header">
      <Header></Header>
      <div class="container contenedeor-title">
        <div>
          <b-img src="sport.png"></b-img>
        </div>
        <div class="my-5">
          <p><span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cupiditate ea facere necessitatibus quam sit? Cumque enim exercitationem laboriosam maxime nesciunt omnis tenetur vero! Assumenda dicta expedita nesciunt odit provident quo.</span><span>Accusamus architecto dignissimos eius in inventore ipsam praesentium repellat sapiente sequi, tempore. Aliquid ea, eius nam nemo reiciendis repellat sunt vitae voluptates. Asperiores harum, similique! Aliquid consectetur cupiditate illum suscipit.</span>
          </p>
        </div>
        <div>
          <b-button pill variant="outline-secondary" class="btn-read">
            READ MORE
          </b-button>
        </div>
      </div>
    </div>
    <WhoAreWe></WhoAreWe>
    <WeUse></WeUse>
    <div class="fondo-priorities">
      <Priorities></Priorities>
    </div>
  </div>
</template>

<script>
import Header from "~/components/Header";
import whoAreWe from "~/components/Who-are-we";
import weUse from "~/components/We-use";
import priorities from "~/components/Priorities";

export default {
  components: {Header, whoAreWe, weUse, priorities},
}
</script>

<style>

* {
  padding: 0;
  margin: 0;
}
.webmain {
  background-color: rgb(0, 0, 0);
}
.fondo-header {
  background-image: url("static/fondos/bg-header.jpg");
  height: 100vh;
  background-size: cover;
}

.contenedeor-title {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100%;
}

div > p {
  color: rgb(255, 255, 255);
  text-align: center;
  font-size: 1.2rem;
}
div > .btn-read {
  background-color: white;
  color: #3ea2d8;
  height: 45px;
  width: 184px;
  font-weight: 500;
}
.fondo-priorities {
  background-image: url("static/fondos/bg-priorities.jpg");
  /*height: 100vh;*/
  /*background-size: cover;*/
}
.title {
  font-family: 'Quicksand',
  'Source Sans Pro',
  -apple-system,
  BlinkMacSystemFont,
  'Segoe UI',
  Roboto,
  'Helvetica Neue',
  Arial,
  sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
</style>
