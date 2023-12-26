<template class="footer">
  <div class="">
    <footer class="footer">
      <div class="footer-flex container footer-grid">
        <div class="footer-tablet">
          <div class="footer-1">
            <a href="./index.html" class="footer-logo">
              <span class="logo-span">Web</span>Studio</a
            >
            <address class="address">
              <ul class="footer-ul list">
                <li class="footer-item">
                  <a
                    class="footer-map"
                    href="https://goo.gl/maps/ebpLASN4Ghw9Ps9j9"
                    target="_blank"
                    rel="noopener"
                    >м. Київ, пр-т Лесі Українки, 26</a
                  >
                </li>
                <li class="footer-item">
                  <a
                    class="footer-contact link"
                    href="mailto:info@devstudio.com"
                    >info@devstudio.com</a
                  >
                </li>
                <li class="footer-item">
                  <a class="footer-contact link" href="tel:+380961111111"
                    >+38 096 111 11 11</a
                  >
                </li>
              </ul>
            </address>
          </div>
          <div class="footer__comin">
            <p class="comin-title">Приєднуйтесь</p>

            <ul class="list employee__social">
              <li>
                <a
                  class="social-item employee-item__social"
                  href="https://www.instagram.com/"
                  target="_blank"
                  rel="noopener"
                >
                  <img src="../icons/instagram.svg" alt="A cat" width="100" />
                </a>
              </li>
              <li>
                <a
                  class="social-item employee-item__social"
                  href="https://twitter.com/?lang=uk"
                  target="_blank"
                  rel="noopener"
                >
                  <svg
                    lang="en"
                    aria-label="twitter link"
                    class="social-icon-footer"
                  >
                    <use
                      href="../icons/facebook-svgrepo-com.svg"
                      height="20"
                    ></use></svg
                ></a>
              </li>
            </ul>
          </div>
        </div>
        <!-- ==============FOOTER FORM======================== -->
        <div class="footer-form">
          <p class="comin-title">Підпишись на розсилку</p>
          <form class="footer-form__colum">
            <input
              type="email"
              class="footer-form-item"
              placeholder="E-mail"
              required
            />
            <button
              submit
              class="link footer-form-link hover-effect"
              type="submit"
            >
              Підписатися
            </button>
          </form>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: 'FooterComponent',
  props: {},
  data() {
    return {};
  },
};
</script>
<style>
.footer {
  background-color: rgb(12, 79, 51);
}
</style>
