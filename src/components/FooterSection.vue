<template>
  <div class="footer">
    <div class="footer__container container">
      <div class="footer__cr">© 2022 Endurophine</div>
      <div class="footer__social-container">
        <a
          class="facebook-icon"
          href="https://www.facebook.com/rowerowymechanik"
          target="__blank"
        >
          <svg
            width="9"
            height="16"
            viewBox="0 0 9 16"
            fill=""
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              d="M5.49859 16V8.70218H7.99501L8.36954 5.85725H5.49859V4.04118C5.49859 3.21776 5.73076 2.65661 6.93596 2.65661L8.47059 2.65599V0.111384C8.2052 0.0775563 7.2942 0 6.23389 0C4.01979 0 2.50399 1.32557 2.50399 3.75942V5.85725H0V8.70218H2.50399V16H5.49859Z"
              fill="#010002"
            />
          </svg>
        </a>
        <a
          class="instagram-icon"
          href="https://www.instagram.com/mechanik_rowerowy/"
          target="__blank"
        >
          <svg
            class="instagram"
            width="22"
            height="22"
            viewBox="0 0 22 22"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              clip-rule="evenodd"
              d="M15.0325 2H6.96724C4.22831 2 2 4.22841 2 6.96735V15.0327C2 17.7717 4.22831 20 6.96724 20H15.0325C17.7717 20 20 17.7716 20 15.0327V6.96735C20.0001 4.22841 17.7717 2 15.0325 2ZM18.4031 15.0326C18.4031 16.8911 16.8911 18.403 15.0326 18.403H6.96724C5.10892 18.4031 3.59705 16.8911 3.59705 15.0326V6.96735C3.59705 5.10903 5.10892 3.59705 6.96724 3.59705H15.0325C16.891 3.59705 18.403 5.10903 18.403 6.96735V15.0326H18.4031ZM6.28571 11.0001C6.28571 8.40055 8.4005 6.28571 11 6.28571C13.5995 6.28571 15.7143 8.40055 15.7143 11.0001C15.7143 13.5996 13.5995 15.7143 11 15.7143C8.4005 15.7143 6.28571 13.5996 6.28571 11.0001ZM11 14.0909C9.29568 14.0909 7.90898 12.7044 7.90898 11C7.90898 9.29553 9.29557 7.90891 11 7.90891C12.7044 7.90891 14.091 9.29553 14.091 11C14.091 12.7044 12.7043 14.0909 11 14.0909Z"
              fill="black"
            />
            <mask
              id="mask0_2_645"
              style="mask-type: alpha"
              maskUnits="userSpaceOnUse"
              x="2"
              y="2"
              width="18"
              height="18"
            >
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M15.0325 2H6.96724C4.22831 2 2 4.22841 2 6.96735V15.0327C2 17.7717 4.22831 20 6.96724 20H15.0325C17.7717 20 20 17.7716 20 15.0327V6.96735C20.0001 4.22841 17.7717 2 15.0325 2ZM18.4031 15.0326C18.4031 16.8911 16.8911 18.403 15.0326 18.403H6.96724C5.10892 18.4031 3.59705 16.8911 3.59705 15.0326V6.96735C3.59705 5.10903 5.10892 3.59705 6.96724 3.59705H15.0325C16.891 3.59705 18.403 5.10903 18.403 6.96735V15.0326H18.4031ZM6.28571 11.0001C6.28571 8.40055 8.4005 6.28571 11 6.28571C13.5995 6.28571 15.7143 8.40055 15.7143 11.0001C15.7143 13.5996 13.5995 15.7143 11 15.7143C8.4005 15.7143 6.28571 13.5996 6.28571 11.0001ZM11 14.0909C9.29568 14.0909 7.90898 12.7044 7.90898 11C7.90898 9.29553 9.29557 7.90891 11 7.90891C12.7044 7.90891 14.091 9.29553 14.091 11C14.091 12.7044 12.7043 14.0909 11 14.0909Z"
                fill="white"
              />
            </mask>
            <g mask="url(#mask0_2_645)">
              <rect width="22" height="22" fill="#fff" />
            </g>
          </svg>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainSection",
};
</script>

<style scoped>
.footer__container {
  justify-content: space-between;
  margin-top: 40px;
}
.footer__cr {
  font-size: 10px;
}
.footer__social-container {
  display: flex;
}
.instagram {
  align-self: center;
}
</style>