<template>
  <div>
    <div class="ie-panel">
      <a href="http://windows.microsoft.com/en-US/internet-explorer/">
        <img src="/images/ie8-panel/warning_bar_0000_us.jpg" height="42" width="820" alt="You are using an outdated browser. For a faster, safer browsing experience, upgrade for free today.">
      </a>
    </div>

    <!-- Preloader -->
    <Preloader />

    <div class="page">
      <!-- Page Header -->
      <AppHeader />

      <!-- Hero Section / Horace Slider -->
      <HeroSection />

      <!-- About Section -->
      <AboutSection />

      <!-- 4 Steps / Process Section -->
      <ProcessSection />

      <!-- Team Section -->
      <TeamSection />

      <!-- Awards & Counters Section -->
      <AwardsSection />

      <!-- Portfolio Section -->
      <PortfolioSection />

      <!-- Latest Blog Posts Section -->
      <BlogSection />

      <!-- Testimonials & Clients Section -->
      <TestimonialsSection />

      <!-- Contact / Get in touch Section -->
      <ContactSection />

      <!-- Footer -->
      <AppFooter />
    </div>

    <div class="snackbars" id="form-output-global"></div>
  </div>
</template>

<script setup>
import { onMounted, nextTick } from 'vue'
import Preloader from './components/Preloader.vue'
import AppHeader from './components/AppHeader.vue'
import HeroSection from './components/HeroSection.vue'
import AboutSection from './components/AboutSection.vue'
import ProcessSection from './components/ProcessSection.vue'
import TeamSection from './components/TeamSection.vue'
import AwardsSection from './components/AwardsSection.vue'
import PortfolioSection from './components/PortfolioSection.vue'
import BlogSection from './components/BlogSection.vue'
import TestimonialsSection from './components/TestimonialsSection.vue'
import ContactSection from './components/ContactSection.vue'
import AppFooter from './components/AppFooter.vue'

onMounted(async () => {
  await nextTick()
  if (typeof window.initSitePlugins === 'function') {
    window.initSitePlugins()
  } else {
    const checkInit = setInterval(() => {
      if (typeof window.initSitePlugins === 'function') {
        window.initSitePlugins()
        clearInterval(checkInit)
      }
    }, 100)
    setTimeout(() => clearInterval(checkInit), 3000)
  }
})
</script>
