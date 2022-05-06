<template>
  <div class="brand">
    <div id="brand" class="brand__container container">
      <div class="brand__cube-1">
        <a href="https://sklep.token-polska.pl/" target="_blank">
          <img class="brand__pic" src="@/assets/img/ebc.png/" loading="lazy" />
        </a>
        <a href="https://sklep.token-polska.pl/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/Logo-biketools-blue-1.png/"
            loading="lazy"
          />
        </a>
        <a href="https://sklep.token-polska.pl/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/momum.png/"
            loading="lazy"
          />
        </a>
      </div>
      <div class="brand__cube-2">
        <a href="https://sklep.token-polska.pl/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/Token.jpeg/"
            loading="lazy"
          />
        </a>
        <a href="https://sklep.token-polska.pl/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/jagwire.jpeg/"
            loading="lazy"
          />
        </a>
      </div>
      <div class="brand__cube-3">
        <a href="https://sklep.token-polska.pl/" target="_blank">
          <img
            class="brand__pic"
            src="@/assets/img/Garbaruk.jpeg/"
            loading="lazy"
          />
        </a>
        <a href="https://sklep.token-polska.pl/" target="_blank">
          <img class="brand__pic" src="@/assets/img/sram.png/" loading="lazy" />
        </a>
      </div>
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
.brand__cube-1,
.brand__cube-2,
.brand__cube-3 {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  width: 100%;
}
.brand__pic {
  max-height: 150px;
}
</style>