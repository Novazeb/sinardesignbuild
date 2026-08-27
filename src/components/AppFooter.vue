<template>
  <footer class="section novi-background bg-cover section-sm footer-classic context-dark" id="contacts">
    <div class="container">
      <a class="brand wow blurIn" href="index.html">
        <img src="/images/logo-sdb-vertical.svg" alt="SINAR DESIGN &amp; BUILD" width="54" height="63"/>
      </a>
      <ul class="contacts-modern footer-classic-list">
        <li class="wow fadeInLeft"><a class="heading-3" href="tel:+6281218939696">+62 812-1893-9696</a></li>
        <li class="wow fadeInRight"><a class="heading-3" href="mailto:novaberkatsyukurzebua@gmail.com">novaberkatsyukurzebua@gmail.com</a></li>
      </ul>
      <div class="footer-location wow fadeInUp" style="color: #c4956a; font-size: 15px; letter-spacing: 2px; margin-bottom: 20px;">
        <span class="mdi mdi-map-marker" style="margin-right: 5px;"></span>JAKARTA, INDONESIA
      </div>
      <ul class="list-inline list-inline-xxl list-social footer-classic-list">
        <li><a class="icon novi-icon mdi mdi-instagram" href="https://instagram.com/zebua_1011" target="_blank" title="Instagram: @zebua_1011"></a></li>
        <li><a class="icon novi-icon mdi mdi-whatsapp" href="https://wa.me/6281218939696" target="_blank" title="WhatsApp: +6281218939696"></a></li>
        <li><a class="icon novi-icon mdi mdi-email" href="mailto:novaberkatsyukurzebua@gmail.com" title="Email: novaberkatsyukurzebua@gmail.com"></a></li>
      </ul>
      <p class="rights">
        <span>&copy;&nbsp;</span>
        <span class="copyright-year">{{ currentYear }}</span>
        <span>&nbsp;</span>
        <span>SINAR DESIGN &amp; BUILD</span>
        <span>. Hak Cipta Dilindungi.</span>
        <span> Design&nbsp;by&nbsp;<strong>Nova</strong></span>
      </p>
    </div>
  </footer>
</template>

<script setup>
import { computed } from 'vue'

const currentYear = computed(() => new Date().getFullYear())
</script>

