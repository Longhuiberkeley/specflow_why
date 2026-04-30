<template>
  <div class="mt-12 mb-24 w-full flex flex-col items-center">
    <!-- The Number Line / Axis -->
    <div class="relative w-3/5 h-1 bg-gray-300 rounded-full flex justify-between items-center">
      <!-- Point 1: Vibe Coding -->
      <div class="relative flex flex-col items-center">
        <div class="w-4 h-4 bg-orange-500 rounded-full border-2 border-white shadow -mt-0.5"></div>
        <div class="absolute top-4 whitespace-nowrap text-center">
          <span class="font-bold text-orange-600">Vibe Coding</span>
          <p class="text-[10px] opacity-60 leading-tight mt-1">Prompt & Pray<br>Loose / Fast</p>
        </div>
      </div>

      <!-- Point 2: Agentic Engineering -->
      <div class="relative flex flex-col items-center">
        <div class="w-4 h-4 bg-blue-500 rounded-full border-2 border-white shadow -mt-0.5"></div>
        <div class="absolute top-4 whitespace-nowrap text-center">
          <span class="font-bold text-blue-600">Agentic Engineering</span>
          <p class="text-[10px] opacity-60 leading-tight mt-1">Tools & Flows<br>Reliable</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/* Ensure the component fits within the slidev layout */
</style>