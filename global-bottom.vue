<script setup>
import { onMounted } from 'vue'

onMounted(() => {
  const style = document.createElement('style')
  style.textContent = `
    #slide-container nav,
    #slidev-goto-dialog,
    #slide-container > div:not(#slide-content),
    #page-root nav,
    .slidev-nav-controls,
    .slidev-toc,
    #slidev-nav,
    .slidev-nav,
    .slidev-outline,
    .slidev-panel {
      display: none !important;
      visibility: hidden !important;
      opacity: 0 !important;
      pointer-events: none !important;
    }
  `
  document.head.appendChild(style)

  const observer = new MutationObserver(() => {
    document.querySelectorAll('#slide-container nav, #slidev-goto-dialog').forEach(el => {
      el.remove()
    })
  })
  observer.observe(document.body, { childList: true, subtree: true })
})
</script>

<template>
  <div />
</template>
