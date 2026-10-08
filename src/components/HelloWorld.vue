<script setup lang="ts">
import {ref} from 'vue'

const count = ref(0)
</script>

<template>
  <header>
    <img id="img-profile" src="./../../assets/kirito.jpg" alt="Profile" />
  </header>

  <section id="center">
    <div>
      <h1>Get started</h1>
      <p>Edit <code>src/App.vue</code> and save to test <code>HMR</code></p>
    </div>
    <button type="button" class="counter" @click="count++">
      Count is {{ count }}
    </button>
  </section>

  <div class="ticks"></div>

  <section id="next-steps">
    <div id="social">
      <svg class="icon" aria-hidden="true">
        <use href="/icons.svg#social-icon"></use>
      </svg>
      <h2>Connect with me</h2>
      <ul>
        <li>
          <a href="https://github.com/MathieuROCANCOURT" target="_blank">
            <svg class="button-icon" aria-hidden="true">
              <use href="/icons.svg#github-icon"></use>
            </svg>
            GitHub
          </a>
        </li>
        <li>
          <a href="https://www.linkedin.com/in/mathieu-rocancourt" target="_blank">
            <svg class="button-icon" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24" height="24"
                 fill="#1665e4" viewBox="0 0 24 24">
              <!--Boxicons v3.0.8 https://boxicons.com | License  https://docs.boxicons.com/free-->
              <path
                  d="M4.983 2.821a2.188 2.188 0 1 0 0 4.376 2.188 2.188 0 1 0 0-4.376M9.237 8.855v12.139h3.769v-6.003c0-1.584.298-3.118 2.262-3.118 1.937 0 1.961 1.811 1.961 3.218v5.904H21v-6.657c0-3.27-.704-5.783-4.526-5.783-1.835 0-3.065 1.007-3.568 1.96h-.051v-1.66zm-6.142 0H6.87v12.139H3.095z"/>
            </svg>
            LinkedIn
          </a>
        </li>
      </ul>
    </div>
  </section>

  <div class="ticks"></div>
  <section id="spacer"></section>
</template>
