<template>
  <div class="brand">
    <div id="brand" class="brand__container container">
      <h5 class="brand__title">
        Swój serwis opieram na sprawdzonych markach z najwyszej światowej półki:
      </h5>
      <!-- <div class="brand__logos"> -->
      <div class="brand__cube-1">
        <a href="https://ebcbrakes.pl/pl" target="_blank">
          <img class="brand__pic" src="@/assets/img/ebc.png/" loading="lazy" />
        </a>
        <a href="https://uniortools.com/pol/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/unior.png/"
            loading="lazy"
          />
        </a>
        <a href="https://www.garbaruk.com/pl_PL/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/garbaruk.png/"
            loading="lazy"
          />
        </a>
        <a href="https://www.momum.cc/en/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/momum.png/"
            loading="lazy"
          />
        </a>
      </div>
      <div class="brand__cube-2">
        <a href="https://jagwire.com/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/jagwire.png/"
            loading="lazy"
          />
        </a>
        <a href="https://sklep.token-polska.pl/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/token.png/"
            loading="lazy"
          />
        </a>
        <a href="https://www.sram.com/en/sram/" target="_blank">
          <img class="brand__pic" src="@/assets/img/sram.png/" loading="lazy" />
        </a>
      </div>
      <!-- </div> -->
    </div>
  </div>
</template>

<script>
export default {
  name: "BrandsSection",
};
</script>

<style scoped>
.brand__container {
  flex-direction: column;
  height: 100vh;
  justify-content: center;
}
.brand__title {
  padding-bottom: 10%;
}
/* .brand__logos {
  display: flex;
} */
.brand__cube-1,
.brand__cube-2 {
  display: flex;
  align-items: center;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-around;
  gap: 25px;
  width: 100%;
  height: 25%;
}
@media (max-width: 1240px) {
  .brand__container {
    height: auto;
    padding-top: 25%;
    padding-bottom: 10%;
  }
  .brand__cube-1 {
    padding-top: 5%;
    padding-bottom: 10%;
  }
}
@media (max-width: 828px) {
  /* .brand__cube-1,
  .brand__cube-2 {
    height: 100;
  } */
  .brand__cube-2 {
    padding-top: 20px;
  }
}
@media (max-width: 553px) {
  .brand__container {
    padding-top: 30%;
  }
  .brand__cube-1 {
    padding-top: 10%;
    /* padding-bottom: 25%; */
  }

  .brand__cube-1,
  .brand__cube-2 {
    height: 35%;
    gap: 30px;
  }
}
@media (max-width: 469px) {
  .brand__cube-1,
  .brand__cube-2 {
    height: 40%;
  }
}
</style>