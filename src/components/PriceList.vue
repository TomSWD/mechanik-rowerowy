<template>
  <div class="price">
    <div id="price" class="price__container container">
      <div class="price__left">
        <img
          class="price__pic"
          src="@/assets/img/photo-1647524146809-f21afd421c90.jpeg/"
          loading="lazy"
        />
      </div>
      <div class="price__right">
        <h5 class="price-txt">
          Nie lubisz zawozić roweru do serwisu i go tam zastawiać? Może nie masz
          na to czasu, albo po prostu Ci się nie chce? Mam na to rozwiązanie –
          Mogę przyjechać do Ciebie. Prawie każdą usterkę jestem w stanie
          naprawić na miejscu. Wszystko, co potrzebne przywiozę ze sobą.
          Skontaktuj się ze mną w najwygodniejszy dla Ciebie sposób, aby omówić
          szczegóły (mailowo, napisz na Facebook’u lub zadzwoń).
        </h5>
        <a
          class="price__btn btn"
          href="https://drive.google.com/file/d/1yaVELXHC70PsLHzW9J6-OFshlksYF_u9/view?usp=sharing"
          target="_blank"
          >OTWÓRZ CENNIK</a
        >
      </div>
      <img
        class="price__pic-resp"
        src="@/assets/img/photo-1648765333763-ee9d2664bf2f.jpeg/"
        loading="lazy"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "PriceList",
};
</script>

<style scoped>
.price__left,
.price__right {
  display: flex;
  flex-direction: column;
  gap: 70px;
  width: 50%;
  height: 100vh;
  justify-content: center;
}
.price__pic {
  width: 90%;
  margin-right: auto;
}
.price__pic-resp {
  display: none;
}
.price__btn {
  display: flex;
  justify-content: center;
  align-items: center;
  font-weight: 700;
  background-color: #d94100;
  width: 330px;
  height: 70px;
  font-size: 25px;
  letter-spacing: 3px;
  border-radius: 25px;
  margin: 0 auto;
}
.price__btn:hover {
  transition: 0.8s;
  background-color: #fff;
  color: #000;
  opacity: 1;
}
@media (max-width: 1240px) {
  .price__left,
  .price__right {
    height: auto;
    padding-top: 15%;
  }
}
@media (max-width: 975px) {
  .price__container {
    flex-direction: column;
    padding-top: 5%;
  }
  .price__left,
  .price__right {
    width: 100%;
    height: auto;
    gap: 20px;
  }
  .price__btn {
    width: 100%;
    margin: 40px auto 50px;
  }
  .price__pic {
    display: none;
  }
  .price__pic-resp {
    display: block;
    padding-top: 50px;
  }
}
@media (max-width: 465px) {
  .price__btn {
    margin: 30px auto 40px;
    font-size: 22px;
  }
}
</style>
