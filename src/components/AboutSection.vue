<template>
  <div class="about">
    <div id="about" class="about__container container">
      <div class="about__txt">
        <h5>
          Od 2010 roku naprawiałem rowery w Krakowie, po przeprowadzce do Krosna
          w 2018 roku, dalej chcę robić to, co kocham i co robię najlepiej.
        </h5>
        <h5>
          Na początku swojej przygody z serwisem rowerowym nie wiedziałem nawet
          którego klucza użyć, żeby przykręcić korbę, nie mówiąc już nawet o
          demontażu wkładu suportu:). Po latach praktyki i szkoleniach, które
          odbyłem bardzo dobrze wiem, który klucz do czego służy i jak naprawić
          piastę wielobiegową w rowerze miejskim lub wyregulować przerzutki Di2
          w rowerze czasowym, czy szosowym.
        </h5>
        <h5>
          Ostatnim miejscem, gdy jeszcze mieszkałem w Krakowie, w którym
          pracowałem był sklep i serwis
          <!-- <a class="about-link" href="https://wertykal.com" target="_blank">
            <img
              class="wertical-logo"
              src="@/assets/img/logo.png/"
              loading="lazy"
            /> -->
          Wertykal
          <!-- </a> -->
          w podkrakowskim Zabierzowie. Dzięki pracy w Wertykalu udało mi się
          uczestniczyć w szkoleniach z komponentów rowerowych marki Campagnolo
          oraz Fulcrum w siedzibie firmy Campagnolo we Włoszech. Przez okres,
          który spędziłem w Wertykalu ucząc się serwisowania rowerów, z którymi
          nie miałem do tej pory nic wspólnego, serwisowałem i przygotowywałem
          do startów rowery wielu zawodnikom kolarstwa szosowego, oraz
          Triathlonistom z okolicznych drużyn jak i z całej Polski.
        </h5>
        <h5>
          Oczywiście nie można spocząć na laurach! W końcu człowiek uczy się
          całe życie, a mechanik rowerowy musi uczyć się jeszcze więcej ;).
          Każdego dnia staram się powiększać swoje umiejętności czytając,
          oglądając czy rozmawiając z mechanikami którzy wiedzą więcej niż ja, w
          niedługiej przyszłości planuję uczestniczyć w kolejnych szkoleniach,
          branża rowerowa w końcu nie stoi w miejscu tylko jest coraz więcej
          nowości, z którymi klienci prędzej czy później do mnie przyjdą.
        </h5>
        <img
          class="about__pic-resp"
          src="@/assets/img/photo-1517263975512-e1e9172f466b.webp/"
          loading="lazy"
        />
        <h5>
          Z racji na zmianę terenu gdzie mieszkam, rowery które serwisuje też
          się zmieniły – z szosowych i czasowych, na rowery MTB z hamulcami
          hydraulicznymi i amortyzatorami. Oczywiście umiejętności też się
          powiększyły, a właściwie odświeżyły! Nie mam problemu z hamulcami
          hydraulicznymi Shimano, Avid czy Magura. Natomiast amortyzatory z
          chęcią przyjmuję na przeglądy kompleksowe jak i na drobne naprawy:).
        </h5>
        <h5>
          Jak tylko Twój jednoślad potrzebuje pomocy z rozregulowanymi
          przerzutkami, krzywym kołem, trzeszczącym łańcuchem czy innymi
          problemami natury technicznej zapraszam do kontaktu!
        </h5>
        <h5>
          Jak nie możesz dowieźć roweru na serwis, nie ma żadnego problemu żebym
          przyjechał naprawić drobną usterkę u Ciebie w domu, lub zabiorę rower
          do siebie i odwiozę pod drzwi twojego domu jak już będzie w 100%
          sprawny :).
        </h5>
      </div>
      <div class="about__pics">
        <img
          class="about__pic-1"
          src="@/assets/img/bike-black-7.png/"
          loading="lazy"
        />
        <img
          class="about__pic-2"
          src="@/assets/img/photo-1649010864808-126f49193b4c.webp/"
          loading="lazy"
        />
        <img
          class="about__pic-3"
          src="@/assets/img/bike-black-5.webp/"
          loading="lazy"
        />
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "AboutSection",
};
</script>

<style scoped>
.about__container {
  padding-top: 5%;
}
.about__txt {
  display: flex;
  max-width: 50%;
  flex-direction: column;
  text-align: center;
  gap: 30px;
  margin: 20px auto 20px;
}

.wertical-logo {
  width: 20px;
  height: 20px;
  margin-left: 5px;
}
.about__pics {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: auto;
  gap: 150px;
}
.about__pic-resp {
  display: none;
}
.about__pic-2 {
  width: 50%;
}
.about__pic-3 {
  width: 80%;
}
@media (max-width: 1240px) {
  .about__txt {
    max-width: 100%;
  }
  .about__pics {
    display: none;
  }
  .about__pic-resp {
    display: block;
  }
}
</style>