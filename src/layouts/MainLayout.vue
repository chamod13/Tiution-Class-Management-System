<template>
  <q-layout view="lHh Lpr lFf" class="bg-white text-black">
    <q-header
      class="bg-transparent text-black q-py-sm absolute-top"
      :class="{ 'bg-white shadow-2': scrollPosition > 50 }"
    >
      <q-toolbar class="container">
        <q-btn flat no-caps dense class="q-mr-sm" to="/">
          <q-icon name="school" size="md" class="q-mr-sm" />
          <span class="text-h6 text-weight-bold">EduMaster</span>
        </q-btn>

        <q-space />

        <div class="gt-sm">
          <q-btn flat no-caps label="Home" to="/" />
          <q-btn flat no-caps label="Features" href="#features" />
          <q-btn flat no-caps label="About" href="#about" />
          <q-btn flat no-caps label="Contact" href="#contact" />
        </div>

        <q-space />

        <div>
          <q-btn flat no-caps label="Login" class="q-mr-sm" />
          <q-btn
            unelevated
            color="primary"
            text-color="white"
            label="Get Started"
            no-caps
            class="q-px-md rounded-borders"
          />
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="bg-black text-white q-py-lg">
      <div class="container text-center">
        <div class="text-h6 q-mb-md">EduMaster</div>
        <div class="q-gutter-sm">
          <q-btn flat round icon="fab fa-facebook" size="sm" />
          <q-btn flat round icon="fab fa-twitter" size="sm" />
          <q-btn flat round icon="fab fa-instagram" size="sm" />
          <q-btn flat round icon="fab fa-linkedin" size="sm" />
        </div>
        <div class="text-grey-5 q-mt-md text-caption">© 2026 EduMaster. All rights reserved.</div>
      </div>
    </q-footer>
  </q-layout>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const scrollPosition = ref(0)

const updateScroll = () => {
  scrollPosition.value = window.scrollY
}

onMounted(() => {
  window.addEventListener('scroll', updateScroll)
})

onUnmounted(() => {
  window.removeEventListener('scroll', updateScroll)
})
</script>

<style scoped>
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}
.rounded-borders {
  border-radius: 8px;
}
</style>
