<template>
  <div class="main__container container">
    <div id="main" class="main__content">
      <h3 class="main__title">Mobilny serwis i mechanik rowerowy</h3>
      <h5 class="main__txt">Mechanik rowerowy z serwisem u Ciebie</h5>
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
  height: 100vh;
  /* padding-top: 5%; */
}
.main__content {
  margin: auto;
}
.main__title,
.main__txt {
  text-transform: uppercase;
}
.main__txt {
  padding-top: 5%;
  padding-bottom: 5%;
}
.main__pic {
  margin: auto;
  width: 80%;
  transform: translateX(5%);
}
@media (max-width: 975px) {
  .main__container {
    flex-direction: column;
    height: auto;
    padding-bottom: 20%;
    padding-top: 15%;
  }
  .main__pic {
    width: 100%;
    transform: none;
  }
}
@media (max-width: 465px) {
  .main__container {
    padding-bottom: 26%;
    padding-top: 15%;
  }
}
</style>