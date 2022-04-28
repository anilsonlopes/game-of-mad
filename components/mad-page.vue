<template>
  <div class="bg-gray-200 h-screen overflow-y-scroll flex flex-col p-5 space-y-5">
    <slot />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'MadPage',
})
</script>
