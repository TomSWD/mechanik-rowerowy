<template>
  <div class="cooperation">
    <div id="cooperation" class="cooperation__container container">
      <div class="cooperation__txt">
        <div class="cooperation__txt-left">
          <h5>Jestem otwarty na propozycję współpracy:</h5>
          <h5>
            - Obsługa serwisowa imprez <br />
            - Wyjazdy jako samochód serwisowy <br />
          </h5>
        </div>
        <div class="cooperation__txt-right">
          <h5>
            Masz jakąś propozycję? <br />
            Napisz lub zadzwoń na pewno się dogadamy!
          </h5>
        </div>
      </div>
      <div class="cooperation__cube-1">
        <a href="https://www.facebook.com/Komonbikes/" target="_blank">
          <img
            class="cooperation__pic"
            src="@/assets/img/komon.png/"
            loading="lazy"
        /></a>
        <a href="https://www.facebook.com/rbikesklep/" target="_blank">
          <img
            class="cooperation__pic"
            src="@/assets/img/10.rbike.png/"
            loading="lazy"
          />
        </a>
        <a href="https://bikeserviceapp.pl/" target="_blank">
          <img
            class="cooperation__pic"
            src="@/assets/img/bikeservice.png/"
            loading="lazy"
          />
        </a>
      </div>
      <div class="cooperation__cube-2">
        <a href="https://www.facebook.com/emtbpodkarpacie/" target="_blank">
          <img
            class="cooperation__pic"
            src="@/assets/img/enduro.png/"
            loading="lazy"
          />
        </a>
        <a
          href="https://www.facebook.com/teammtbmandslostarkkrosno"
          target="_blank"
        >
          <img
            class="cooperation__pic"
            src="@/assets/img/team.png/"
            loading="lazy"
          />
        </a>
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
  padding-top: 5%;
}
.cooperation__txt {
  display: flex;
  flex-direction: row;
  gap: 30;
  margin-bottom: 10%;
}
.cooperation__txt-left {
  padding-right: 10px;
}
.cooperation__txt-left,
.cooperation__txt-right {
  width: 50%;
}
/* .cooperation__logos {
  margin-top: 8%;
  height: 25%;
  display: flex;
  justify-content: space-between;
  flex-direction: column;
} */
.cooperation__cube-1,
.cooperation__cube-2 {
  /* display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  height: 10%; */
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
  .cooperation__container {
    height: auto;
    padding-top: 25%;
  }
  .cooperation__cube-1 {
    padding-top: 5%;
    padding-bottom: 10%;
  }
}
@media (max-width: 975px) {
  .cooperation__txt {
    flex-direction: column;
    padding-bottom: 2%;
    gap: 20px;
  }
  .cooperation__txt-left,
  .cooperation__txt-right {
    width: 100%;
  }
}
@media (max-width: 469px) {
  .cooperation__cube-1 {
    padding-top: 10%;
  }
  .cooperation__cube-1,
  .cooperation__cube-2 {
    height: 50%;
  }
}
</style>