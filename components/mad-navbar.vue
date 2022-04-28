<template>
  <div class="rounded-xl px-5 py-3 bg-white text-gray-500 sticky bottom-5">
    <div class="flex justify-around space-x-2">
      <nuxt-link
        to="/"
        class="flex flex-col items-center justify-center space-y-2 text-green-700"
      >
        <svg width="1.13em" height="1em" viewBox="0 0 576 512">
          <path
            fill="currentColor"
            d="M575.8 255.5c0 18-15 32.1-32 32.1h-32l.7 160.1c0 2.8-.2 5.4-.5 8.1V472c0 22.1-17.9 40-40 40h-16c-1.1 0-2.2-.9-3.3-.1c-1.4-.8-2.8.1-4.2.1H392c-22.1 0-40-17.9-40-40v-88c0-17.7-14.3-32-32-32h-64c-17.7 0-32 14.3-32 32v88c0 22.1-17.9 40-40 40h-55.9c-1.5 0-3-.1-4.5-.2c-1.2.1-2.4.2-3.6.2h-16c-22.09 0-40-17.9-40-40V360c0-.9.03-1.9.09-2.8v-69.6H32.05C14.02 287.6 0 273.5 0 255.5c0-9 3.004-17 10.01-24L266.4 8.016c7-7.014 15-8.016 22-8.016s15 2.004 21.1 7.014L564.8 231.5c8 7 12.1 15 11 24z"
          ></path>
        </svg>
        <span>Home</span>
      </nuxt-link>
      <nuxt-link to="/ranking" class="flex flex-col items-center justify-center space-y-2">
        <svg width="1.25em" height="1em" viewBox="0 0 640 512">
          <path
            fill="currentColor"
            d="M406.1 61.65c9.3 1.44 13.3 12.94 6.5 19.76l-38 36.69l9 52c.5 9.4-8.3 16.6-16.9 12.3l-46.5-24.5l-46.9 24.8c-8.6 4.3-18.3-2.9-16.9-12.2l9-52.1l-38-36.99c-6.8-6.82-2.8-18.32 6.5-19.76l52.3-7.54l23.6-47.778c4.3-8.621 16.5-8.262 20.4 0l23.6 47.778l52.3 7.54zM384 256c17.7 0 32 14.3 32 32v192c0 17.7-14.3 32-32 32H256c-17.7 0-32-14.3-32-32V288c0-17.7 14.3-32 32-32h128zm-224 64c17.7 0 32 14.3 32 32v128c0 17.7-14.3 32-32 32H32c-17.67 0-32-14.3-32-32V352c0-17.7 14.33-32 32-32h128zm288 96c0-17.7 14.3-32 32-32h128c17.7 0 32 14.3 32 32v64c0 17.7-14.3 32-32 32H480c-17.7 0-32-14.3-32-32v-64z"
          ></path>
        </svg>
        <span>Ranking</span>
      </nuxt-link>
      <nuxt-link to="/" class="flex flex-col items-center justify-center space-y-2">
        <svg width="1em" height="1em" viewBox="0 0 24 24">
          <path
            fill="currentColor"
            d="M12 17.27L18.18 21l-1.64-7.03L22 9.24l-7.19-.61L12 2L9.19 8.63L2 9.24l5.46 4.73L5.82 21z"
          ></path>
        </svg>
        <span>Contest</span>
      </nuxt-link>
      <nuxt-link to="/" class="flex flex-col items-center justify-center space-y-2">
        <svg width="1em" height="1em" viewBox="0 0 256 256">
          <path
            fill="currentColor"
            d="M216 40H40a16 16 0 0 0-16 16v128a16 16 0 0 0 16 16h59.5l14.8 24.7a15.9 15.9 0 0 0 27.4 0l14.8-24.7H216a16 16 0 0 0 16-16V56a16 16 0 0 0-16-16Zm-56 104H96a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16Zm0-32H96a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16Z"
          ></path>
        </svg>
        <span>Messages</span>
      </nuxt-link>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'MadNavbar',
})
</script>
