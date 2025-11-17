<template>
  <section class="contact section-padding" id="section_6">
    <div class="svg-container">
      <h3 class="about-heading">Say hi</h3>
    </div>

    <div class="container">
      <div class="row">
        <div class="clearfix"></div>

        <div class="col-lg-3 col-md-6 col-12 pe-lg-0">
          <div class="contact-info contact-info-border-start d-flex flex-column">
            <strong class="site-footer-title d-block mb-3">Services</strong>

            <ul class="footer-menu">
              <li class="footer-menu-item"><a href="#section_3" class="footer-menu-link">Websites</a></li>

              <li class="footer-menu-item"><a href="#section_3" class="footer-menu-link">Game</a></li>

              <li class="footer-menu-item"><a href="#section_3" class="footer-menu-link">Media</a></li>

              <li class="footer-menu-item"><a href="#section_3" class="footer-menu-link">Content</a></li>
            </ul>

            <strong class="site-footer-title d-block mt-4 mb-3">Stay connected</strong>

            <ul class="social-icon">
              <li class="social-icon-item"><a href="https://github.com/triek" target="_blank" class="social-icon-link bi-github"></a></li>

              <li class="social-icon-item">
                <a href="https://www.linkedin.com/in/trietkhuong/" target="_blank" class="social-icon-link bi-linkedin"></a>
              </li>

              <li class="social-icon-item">
                <a href="https://www.behance.net/trietkhuongminh" target="_blank" class="social-icon-link bi-behance"></a>
              </li>

              <li class="social-icon-item">
                <a href="https://www.facebook.com/mingtriet.khuong/" target="_blank" class="social-icon-link bi-facebook"></a>
              </li>
            </ul>
          </div>
        </div>

        <div class="col-lg-3 col-md-6 col-12 ps-lg-0">
          <div class="contact-info d-flex flex-column">
            <strong class="site-footer-title d-block mb-3">About</strong>

            <p class="mb-2">Tristan is an intern developer. Feel free to get in touch with me.</p>

            <strong class="site-footer-title d-block mt-4 mb-3">Email</strong>

            <p class="mb-2">
              <a href="mailto:ITITDK22041@student.hcmiu.edu.vn"> s225641143@deakin.edu.au </a>
            </p>
          </div>
        </div>

        <div class="col-lg-6 col-12 mt-5 mt-lg-0">
          <strong class="site-footer-title d-block m-3">Start a project</strong>
          <ContactForm />
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import ContactForm from './ContactForm.vue';
</script>
