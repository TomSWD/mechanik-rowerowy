<template>
  <div class="contact">
    <div id="contact" class="contact__container container">
      <div class="contact__left">
        <img
          class="contact__logo"
          src="@/assets/img/mechanik-logo.jpeg/"
          loading="lazy"
        />
        <div class="contact__txt">
          <h5 class="phone">
            Telefon: <a href="tel:+48609595205">+48 609 595 205</a>
          </h5>
          <h5 class="email">
            E-mail:
            <a href="mailto:serwis@rowerowymechanik.pl"
              >serwis@rowerowymechanik.pl</a
            >
          </h5>
          <h5 class="fb">
            Facebook:
            <a href="https://www.facebook.com/rowerowymechanik"
              >facebook.com/rowerowymechanik</a
            >
          </h5>
          <h5 class="instagram">
            Instagram:
            <a href="https://www.instagram.com/mechanik_rowerowy/"
              >instagram.com/mechanik_rowerowy</a
            >
          </h5>
        </div>
      </div>
      <div class="contact__right">
        <iframe
          class="map"
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4620.352645091474!2d21.76872653668293!3d49.68951528528019!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x8e6f4ebfc2b601cd!2sMechanik%20Rowerowy!5e0!3m2!1spl!2spl!4v1650624904229!5m2!1spl!2spl"
          width="600"
          height="450"
          style="border: 0"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
        ></iframe>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactSection",
};
</script>

<style scoped>
.contact__left,
.contact__right {
  display: flex;
  flex-direction: column;
  width: 50%;
  height: 100vh;
  justify-content: center;
  margin-top: 5%;
}
.contact__txt {
  display: flex;
  flex-direction: column;
  margin-right: auto;
}
.contact__logo {
  width: 70%;
  margin-right: auto;
  padding: 0px 0px 20px 0px;
}
.map {
  max-width: 100%;
  align-self: center;
}
@media (max-width: 1240px) {
  .contact__container {
    height: auto;
    padding-top: 12%;
    padding-bottom: 10%;
  }
  .contact__left,
  .contact__right {
    width: 100%;
    height: auto;
  }
  .contact__left {
    display: block;
    flex-direction: row;
  }
  .contact__txt,
  .contact__logo {
    margin: auto;
  }
  .contact__txt {
    font-size: 16px;
  }
  .contact__logo {
    padding-bottom: 0px;
  }
  .map {
    padding-top: 20px;
    width: 100vw;
  }
}
@media (max-width: 975px) {
  .contact__container {
    flex-direction: column;
  }
  .contact__left {
    flex-direction: column;
    padding-top: 40px;
  }
  .contact__logo {
    width: 100%;
    padding-bottom: 10%;
  }
}
@media (max-width: 465px) {
  .contact__txt {
    font-size: 14px;
  }
  .map {
    padding-top: 40px;
  }
}
</style>