<template>
  <div class="flex items-center">
    <div class="flex-1 text-gray-800 font-medium">Start daily workout</div>
    <div
      class="w-10 h-10 flex justify-center items-center bg-green-500 text-gray-200 rounded-lg"
    >
      <svg width="1em" height="1em" viewBox="0 0 24 24">
        <path
          fill="currentColor"
          d="M8.59 16.59L13.17 12L8.59 7.41L10 6l6 6l-6 6l-1.41-1.41z"
        ></path>
      </svg>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'MadAction',
})
</script>
