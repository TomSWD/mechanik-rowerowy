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
          <a class="phone" href="tel:+48609595205" target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="black"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-phone"
            >
              <path
                d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"
              ></path></svg
            >+48 609 595 205</a
          >
          <a
            class="email"
            href="mailto:serwis@rowerowymechanik.pl"
            target="_blank"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="22"
              height="22"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-send"
            >
              <line x1="22" y1="2" x2="11" y2="13"></line>
              <polygon points="22 2 15 22 11 13 2 9 22 2"></polygon>
            </svg>
            serwis@rowerowymechanik.pl</a
          >
          <a
            class="facebook"
            href="https://www.facebook.com/rowerowymechanik"
            target="_blank"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="black"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-facebook"
            >
              <path
                d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"
              ></path>
            </svg>
            facebook.com/rowerowymechanik</a
          >
          <a
            class="instagram"
            href="https://www.instagram.com/mechanik_rowerowy/"
            target="_blank"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="white"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-instagram"
            >
              <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
              <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path>
              <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
            </svg>
            instagram.com/mechanik_rowerowy</a
          >
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
  gap: 5px;
}
.phone,
.email,
.instagram,
.facebook {
  display: flex;
  gap: 10px;
  align-items: center;
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