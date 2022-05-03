<template>
  <div class="cooperation">
    <div class="cooperation__container container">
      <div class="cooperation__left">
        <h5>Jestem otwarty na propozycję współpracy</h5>
        <br />
        <h5>
          Obsługa serwisowa imprez <br />
          Wyjazdy jako samochód serwisowy <br />
          Mechanik na godziny u Ciebie w serwisie
        </h5>
        <br />
        <h5>
          Masz jakąś propozycję? <br />
          Napisz lub zadzwoń na pewno się dogadamy!
        </h5>
      </div>
      <div class="cooperation__right">
        <div class="cooperation__cube-1">
          <a href="https://www.facebook.com/emtbpodkarpacie" target="_blank">
            <img
              class="cooperation__pic-1"
              src="@/assets/img/endu.png/"
              loading="lazy"
            />
          </a>
          <a href="https://www.facebook.com/emtbpodkarpacie" target="_blank">
            <img
              class="cooperation__pic-2"
              src="@/assets/img/komon.jpeg/"
              loading="lazy"
            />
          </a>
          <a href="https://bikeserviceapp.pl/" target="_blank">
            <img
              class="cooperation__pic-3"
              src="@/assets/img/bsa.png/"
              loading="lazy"
            />
          </a>
        </div>
        <div class="cooperation__cube-2">
          <a href="https://sklep.token-polska.pl/" target="_blank">
            <img
              class="cooperation__pic-4"
              src="@/assets/img/Token.jpeg/"
              loading="lazy"
            />
          </a>
          <a href="https://www.facebook.com/rbikesklep/" target="_blank">
            <img
              class="cooperation__pic-4"
              src="@/assets/img/rbike.png/"
              loading="lazy"
            />
          </a>
          <a
            href="https://www.facebook.com/teammtbmandslostarkkrosno"
            target="_blank"
          >
            <img
              class="cooperation__pic-4"
              src="@/assets/img/lo-stark-mtb.jpeg/"
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
.cooperation__left,
.cooperation__right {
  display: flex;
  flex-direction: column;
  width: 50%;
  height: 100vh;
  justify-content: center;
}
/* .cooperation__right {
  height: 100vh;
  width: 50%;
  display: flex;
  justify-content: space-between;
  flex-direction: row;
} */
.cooperation__cube-1 {
  display: flex;
  flex-direction: column;
  max-width: 25%;
}
.cooperation__cube-2 {
  max-width: 70%;
}
</style>