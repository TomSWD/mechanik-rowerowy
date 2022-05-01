<template>
  <div class="main__container container">
    <div id="main" class="main__content">
      <h3 class="main__title">Mobilny serwis i mechanik rowerowy</h3>
      <h5 class="main__txt">
        z dojazdem do klienta w Krośnie i na terenie województwa Podkarpackiego
      </h5>
      <img
        class="main__logo"
        src="@/assets/img/mechanik-logo.jpeg/"
        loading="lazy"
      />
    </div>
    <img
      class="main__pic"
      src="@/assets/img/bike-black-2.webp/"
      loading="lazy"
    />
  </div>
</template>

<script>
export default {
  name: "MainSection",
};
</script>

<style scoped>
.main__container {
  flex-direction: row;
  text-align: center;
  height: 100vh;
  padding-top: 5%;
}
.main__content {
  margin: auto;
}
.main__title,
.main__txt {
  text-transform: uppercase;
}
.main__logo {
  width: 70%;
  padding-top: 70px;
}
.main__pic {
  margin: auto;
  width: 50%;
}
@media (max-width: 975px) {
  .main__container {
    flex-direction: column;
    height: auto;
    padding-bottom: 5%;
  }
  .main__pic {
    display: none;
  }
}
</style>