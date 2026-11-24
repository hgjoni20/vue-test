<script setup>
import { ref } from 'vue';
const clicks = ref(0);
</script>

<template>
  <main style="font-family: system-ui, sans-serif; padding: 2rem; background: #111827; color: #ecfdf5; min-height: 100vh;">
    <h1>Vue 3 Static Bundle on HostShell</h1>
    <p>Compiled into static HTML/CSS/JS inside <code>dist/</code>.</p>
    <button
      @click="clicks++"
      style="padding: 0.6rem 1.2rem; font-size: 1rem; cursor: pointer; border-radius: 6px; border: none; background: #10b981; color: #064e3b; font-weight: bold;"
    >
      Vue reactivity clicks: {{ clicks }}
    </button>
  </main>
</template>
