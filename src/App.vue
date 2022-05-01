<template>
  <MenuSection />
  <MainSection />
  <PriceList />
  <AboutSection />
  <ContactSection />
  <FooterSection />
</template>

<script>
import "@/assets/styles/reset.css";
import "@/assets/styles/global.css";

import MenuSection from "./components/MenuSection.vue";
import MainSection from "./components/MainSection.vue";
import PriceList from "./components/PriceList.vue";
import AboutSection from "./components/AboutSection.vue";
import ContactSection from "./components/ContactSection.vue";
import FooterSection from "./components/FooterSection.vue";

export default {
  name: "App",
  components: {
    MenuSection,
    MainSection,
    PriceList,
    AboutSection,
    ContactSection,
    FooterSection,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;900&display=swap");
</style>
