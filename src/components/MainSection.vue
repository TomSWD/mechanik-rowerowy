<template>
  <div class="main__container container">
    <div id="main" class="main__content">
      <h3 class="main__title">mechanik rowerowy</h3>
      <h5 class="main__txt">
        Profesjonalny serwis z moźliwym dojazdem do Ciebie
      </h5>
      <h5 class="main__hours">
        Serwis stacjonarny czynny w godzinach: <br />
        - poniedziałek: 9-19 <br />
        - wtorek - środa: 9-17 <br />
        - czwartek: 9-19<br />
        - piatek: 9-17
      </h5>
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
  padding-bottom: 25%;
}
.main__pic {
  margin: auto;
  width: 80%;
  transform: translateX(5%);
  /* overflow-x: hidden; */
}
@media (max-width: 1240px) {
  .main__container {
    height: auto;
    padding-top: 5%;
  }
  .main__txt {
    padding-bottom: 20%;
  }
}
@media (max-width: 975px) {
  .main__container {
    flex-direction: column;
    height: auto;
    padding-bottom: 5%;
    padding-top: 10%;
  }
  .main__txt {
    padding-bottom: 12%;
  }
  .main__pic {
    width: 100%;
    transform: none;
    padding-top: 5%;
  }
}
@media (max-width: 465px) {
  .main__container {
    padding-bottom: 26%;
    padding-top: 15%;
  }
}
</style>