<template>
  <div class="menu">
    <div class="menu__container container">
      <a href="#">
        <svg
          class="nav__burger"
          width="36"
          height="26"
          viewBox="0 0 36 26"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <rect width="36" height="2" fill="#fff" />
          <rect y="12" width="36" height="2" fill="#fff" />
          <rect y="24" width="36" height="2" fill="#fff" />
        </svg>
      </a>
      <div class="menu__links">
        <a class="menu__link" href="#price">CENNIK</a>
        <a class="menu__link" href="#cooperation">WSPÓŁPRACA</a>
        <a class="menu__link" href="#brand">MOJE MARKI</a>
        <a class="menu__link" href="#about">O MNIE</a>
        <a class="menu__link" href="#contact">KONTAKT</a>
        <a></a>
      </div>
      <div class="menu__social">
        <a
          class="facebook-icon icon"
          href="https://www.facebook.com/rowerowymechanik"
          target="__blank"
        >
          <svg
            width="35"
            height="35"
            viewBox="0 0 48 48"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <circle cx="24" cy="24" r="24" fill="#F6F7FB" />
            <path
              d="M30 14H27C25.6739 14 24.4021 14.5268 23.4645 15.4645C22.5268 16.4021 22 17.6739 22 19V22H19V26H22V34H26V26H29L30 22H26V19C26 18.7348 26.1054 18.4804 26.2929 18.2929C26.4804 18.1054 26.7348 18 27 18H30V14Z"
              stroke="black"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </svg>
        </a>
        <a
          class="instagram-icon icon"
          href="https://www.instagram.com/mechanik_rowerowy/"
          target="__blank"
        >
          <svg
            width="35"
            height="35"
            viewBox="0 0 48 48"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <circle cx="24" cy="24" r="24" fill="#F6F7FB" />
            <path
              d="M28.5 15H19.5C17.0147 15 15 17.0147 15 19.5V28.5C15 30.9853 17.0147 33 19.5 33H28.5C30.9853 33 33 30.9853 33 28.5V19.5C33 17.0147 30.9853 15 28.5 15Z"
              stroke="black"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
            <path
              d="M27.6 23.4325C27.7111 24.1816 27.5832 24.9465 27.2344 25.6187C26.8857 26.2908 26.3339 26.8358 25.6575 27.1762C24.9811 27.5167 24.2146 27.6352 23.467 27.5149C22.7194 27.3946 22.0288 27.0416 21.4934 26.5062C20.958 25.9708 20.605 25.2801 20.4847 24.5325C20.3644 23.7849 20.4829 23.0184 20.8233 22.3421C21.1638 21.6657 21.7088 21.1139 22.3809 20.7652C23.053 20.4164 23.818 20.2885 24.567 20.3995C25.3311 20.5128 26.0384 20.8689 26.5846 21.415C27.1307 21.9612 27.4867 22.6685 27.6 23.4325Z"
              stroke="black"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
            <path
              d="M28.9502 19.0503H28.9584"
              stroke="black"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
          </svg>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MenuSection",
};
</script>

<style scoped>
.menu {
  position: fixed;
  z-index: 1;
  margin: 0 auto;
  padding-top: 10px;
  width: 100%;
  background: #000;
}
.menu__container {
  justify-content: space-between;
  align-items: center;
  box-shadow: 0px 4px 5px -5px rgba(250, 248, 248, 0.336);
}
.nav__burger {
  display: none;
}
.menu__links {
  display: flex;
  width: 100%;
  justify-content: space-between;
}
.menu__link {
  padding: 10px 10px;
  border-radius: 20px;
  font-weight: 400;
}
.menu__link:hover {
  background-color: #fff;
  color: #000;
  opacity: 1;
  transition: 0.8s;
}
.menu__social {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  /* display: flex;
  justify-content: space-between;
  width: 75px; */
}
@media (max-width: 1240px) {
  .menu {
    position: static;
  }
  .menu__links {
    display: none;
  }
  .nav__burger {
    display: block;
  }
}
</style>