<template>
  <div class="cooperation">
    <div id="cooperation" class="cooperation__container container">
      <div class="cooperation__txt">
        <div class="cooperation__txt-left">
          <h5>Jestem otwarty na propozycję współpracy:</h5>
          <h5>
            - Obsługa serwisowa imprez <br />
            - Wyjazdy jako samochód serwisowy <br />
            - Mechanik na godziny u Ciebie w serwisie
          </h5>
        </div>
        <div class="cooperation__txt-right">
          <h5>
            Masz jakąś propozycję? <br />
            Napisz lub zadzwoń na pewno się dogadamy!
          </h5>
        </div>
      </div>
      <div class="cooperation__logos">
        <div class="cooperation__cube-1">
          <a href="https://www.facebook.com/Komonbikes/" target="_blank">
            <img
              class="cooperation__pic"
              src="@/assets/img/komon.jpeg/"
              loading="lazy"
            />
          </a>
          <a href="https://www.facebook.com/rbikesklep/" target="_blank">
            <img
              class="cooperation__pic"
              src="@/assets/img/rbike.png/"
              loading="lazy"
            />
          </a>
          <a href="https://bikeserviceapp.pl/" target="_blank">
            <img
              class="cooperation__pic"
              src="@/assets/img/bsa.png/"
              loading="lazy"
            />
          </a>
        </div>
        <div class="cooperation__cube-2">
          <a href="https://sklep.token-polska.pl/" target="_blank">
            <img
              class="cooperation__pic"
              src="@/assets/img/Token.jpeg/"
              loading="lazy"
            />
          </a>

          <a
            href="https://www.facebook.com/teammtbmandslostarkkrosno"
            target="_blank"
          >
            <img
              class="cooperation__pic"
              src="@/assets/img/lo-stark-mtb.jpeg/"
              loading="lazy"
            />
          </a>
        </div>
        <div class="cooperation__cube-3">
          <a href="https://www.facebook.com/emtbpodkarpacie" target="_blank">
            <img
              class="cooperation__pic"
              src="@/assets/img/endu.png/"
              loading="lazy"
            />
          </a>
          <a
            href="https://www.facebook.com/teammtbmandslostarkkrosno"
            target="_blank"
          >
            <img
              class="cooperation__pic macpol-pic"
              src="@/assets/img/logoMACpol.png/"
              loading="lazy"
            />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CooperationSection",
};
</script>

<style scoped>
.cooperation__container {
  flex-direction: column;
  height: 100vh;
  justify-content: center;
}
.cooperation__txt {
  display: flex;
  flex-direction: row;
  gap: 30px;
  padding-bottom: 70px;
}
.cooperation__txt-left,
.cooperation__txt-right {
  width: 50%;
}
.cooperation__cube-1,
.cooperation__cube-2,
.cooperation__cube-3 {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}
.cooperation__pic {
  max-height: 150px;
}
@media (max-width: 975px) {
  .cooperation__txt {
    flex-direction: column;
    padding-bottom: 50px;
  }
  cooperation__txt-left,
  .cooperation__txt-right {
    width: 100%;
  }
}
</style>