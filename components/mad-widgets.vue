<template>
  <div class="grid grid-cols-2 gap-4">
    <div class="bg-green-500 text-white rounded-lg px-4 py-5 col-span-2">
      <div class="opacity-50">Tournament</div>
      <div class="font-medium text-lg">Autumn Cup</div>
      <div class="flex space-x-20 pt-4">
        <div>
          <div class="opacity-50">Entry fee</div>
          <div class="font-medium">100</div>
        </div>
        <div>
          <div class="opacity-50">End date</div>
          <div class="font-medium">10.07.2022</div>
        </div>
      </div>
    </div>
    <div class="bg-blue-500 text-white rounded-2xl px-4 py-5">
      <div class="flex items-center">
        <div class="flex-1 font-medium">Progress</div>
        <div
          class="w-10 h-10 rounded-lg border border-gray-300 flex justify-center items-center"
        >
          <svg width="1em" height="1em" viewBox="0 0 24 24">
            <path
              fill="currentColor"
              d="M13 2.03v2.02c4.39.54 7.5 4.53 6.96 8.92c-.46 3.64-3.32 6.53-6.96 6.96v2c5.5-.55 9.5-5.43 8.95-10.93c-.45-4.75-4.22-8.5-8.95-8.97m-2 .03c-1.95.19-3.81.94-5.33 2.2L7.1 5.74c1.12-.9 2.47-1.48 3.9-1.68v-2M4.26 5.67A9.885 9.885 0 0 0 2.05 11h2c.19-1.42.75-2.77 1.64-3.9L4.26 5.67M2.06 13c.2 1.96.97 3.81 2.21 5.33l1.42-1.43A8.002 8.002 0 0 1 4.06 13h-2m5.04 5.37l-1.43 1.37A9.994 9.994 0 0 0 11 22v-2a8.002 8.002 0 0 1-3.9-1.63M12.5 7v5.25l4.5 2.67l-.75 1.23L11 13V7h1.5Z"
            ></path>
          </svg>
        </div>
      </div>
      <div class="text-5xl">43</div>
      <div class="opacity-50">Learned words</div>
    </div>
    <div class="bg-red-500 text-white rounded-2xl px-4 py-5">
      <div class="flex items-center">
        <div class="flex-1 font-medium">Arena score</div>
        <div
          class="w-10 h-10 rounded-lg border border-gray-300 flex justify-center items-center"
        >
          <svg width="1em" height="1em" viewBox="0 0 24 24">
            <path
              fill="currentColor"
              d="M20 2H4v2l5.81 4.36a7.004 7.004 0 0 0-4.46 8.84a6.996 6.996 0 0 0 8.84 4.46a7 7 0 0 0 0-13.3L20 4V2m-5.06 17.5L12 17.78L9.06 19.5l.78-3.33l-2.59-2.24l3.41-.29L12 10.5l1.34 3.14l3.41.29l-2.59 2.24l.78 3.33Z"
            ></path>
          </svg>
        </div>
      </div>
      <div class="text-5xl">77</div>
      <div class="opacity-50">out of 100</div>
    </div>
    <div class="bg-purple-500 text-white rounded-2xl px-4 py-5">
      <div class="flex items-center">
        <div class="flex-1 font-medium">Ranking</div>
        <div
          class="w-10 h-10 rounded-lg border border-gray-300 flex justify-center items-center"
        >
          <svg width="1em" height="1em" viewBox="0 0 48 48">
            <g fill="currentColor">
              <path
                fillRule="evenodd"
                d="M35 6a3 3 0 0 0-3 3v30a3 3 0 0 0 3 3h4a3 3 0 0 0 3-3V9a3 3 0 0 0-3-3h-4Zm-1 3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v30a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V9ZM19 21a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v18a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3V21Zm3-1a1 1 0 0 0-1 1v18a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1V21a1 1 0 0 0-1-1h-4Z"
                clipRule="evenodd"
              ></path>
              <path
                d="M6 33a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-6Z"
              ></path>
            </g>
          </svg>
        </div>
      </div>
      <div class="text-5xl">1239</div>
      <div class="opacity-50">you beat 10% of usuers</div>
    </div>
    <div class="bg-yellow-500 text-white rounded-2xl px-4 py-5">
      <div class="flex items-center">
        <div class="flex-1 font-medium">Following</div>
        <div
          class="w-10 h-10 rounded-lg border border-gray-300 flex justify-center items-center"
        >
          <svg width="1em" height="1em" viewBox="0 0 24 24">
            <path
              fill="currentColor"
              d="M13 14.062V22H4a8 8 0 0 1 9-7.938zM12 13c-3.315 0-6-2.685-6-6s2.685-6 6-6s6 2.685 6 6s-2.685 6-6 6zm5.793 6.914l3.535-3.535l1.415 1.414l-4.95 4.95l-3.536-3.536l1.415-1.414l2.12 2.121z"
            ></path>
          </svg>
        </div>
      </div>
      <div class="text-5xl">10</div>
      <div class="opacity-50">students</div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'MadWidgets',
})
</script>
