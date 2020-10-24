<template>
  <div class="container mx-auto px-3 bg-black-200 h-screen">
    <!-- <div class="flex justify-center"></div> -->
    <div class="flex justify-center align-center">
      <div>
        <div
          class="max-w-sm rounded overflow-hidden shadow-lg mt-20 pb-4 bg-white"
        >
          <div class="px-6 py-4 flex flex-wrap justify-center">
            <img
              src="~/assets/images/numago-logo.svg"
              alt=""
              class="mt-4 h-20 w-3/4"
            />
            <p class="text-gray-700 text-base mt-4">
              <b>Numago - Internetbureau</b> <br />
              <i>Software Development, IT Consultancy, Online Marketing</i>
            </p>
            <div class="w-full text-gray-700">
              <ul class="mt-4">
                <li class="_list-item">
                  <svg
                    class="fill-current w-h h-4 mr-2 inline-block justify-center"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                  >
                    <title>Email</title>
                    <path
                      d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"
                    />
                    <path
                      d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"
                    />
                  </svg>
                  {{ email }}
                </li>
                <li class="_list-item">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 652 243"
                    class="fill-current w-h h-3 mr-2 inline-block"
                  >
                    <title>KVK</title>
                    <path
                      d="M528.55 143c-1.52-2.5-2.6-3.91-3.91-4.67a6.64 6.64 0 00-8.91 2.5c-1.08 2.06-1.08 6.52-1.08 8v62.87h-71V34.14h71V109l54.11-74.87h78.13l-61.18 78.13L652 211.7h-81zm-252.43 68.7h80.2l65.85-177.45h-71.83l-31 98.88h-.54l-30.75-99H213.2zm-148.76 0h81L142 112.27l61.18-78.13h-78.1L71 109V34.14H0v177.45h71v-62.81c0-1.52 0-6.08 1.09-8a6.64 6.64 0 018.91-2.5c1.3.76 2.39 2.17 3.91 4.67z"
                    />
                  </svg>
                  76360601
                </li>
              </ul>
            </div>
            <!-- <div class="font-bold text-xl mb-2 mt-10 text-center">
            Binnekort online..
          </div> -->
          </div>
          <!-- <div
            class="font-bold text-grey-700 text-xl py-3 mt-2 mb-2 text-center"
          >
            Binnenkort online..
          </div> -->
        </div>
        <div class="max-w-sm pt-6">
          <a :href="'mailto:' + email">
            <button class="_blue-button _block-button">
              <svg
                class="fill-current w-h h-4 mr-2"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
              >
                <path
                  d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"
                />
                <path
                  d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"
                />
              </svg>
              <span>E-mail</span>
            </button>
          </a>
          <!-- <n-link to="about"> -->
          <a :href="whatsappLink">
            <button class="_green-button _block-button">
              <svg
                class="fill-current w-4 h-4 mr-2"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 1000 1000"
              >
                <path
                  d="M845.09 155.4c-91.53-91.64-213.26-142.13-343-142.18C234.9 13.22 17.41 230.7 17.3 498A484 484 0 0082 740.39L13.24 991.63l257-67.42a484.52 484.52 0 00231.69 59h.2c267.2 0 484.72-217.5 484.82-484.82C987 368.85 936.63 247 845.09 155.4zm-343 745.94H502a402.45 402.45 0 01-205.1-56.17l-14.71-8.73-152.52 40 40.71-148.7-9.58-15.25A402 402 0 0199.16 498C99.25 275.86 280 95.1 502.3 95.1c107.63 0 208.81 42 284.89 118.18s118 177.41 117.91 285.09c-.1 222.19-180.86 402.97-402.96 402.97zm221-301.81c-12.11-6.06-71.67-35.36-82.77-39.41s-19.18-6.06-27.26 6.06-31.29 39.42-38.36 47.51-14.13 9.09-26.24 3-51.15-18.86-97.42-60.13c-36-32.12-60.33-71.79-67.39-83.92S383 454 389 448c5.45-5.43 12.11-14.15 18.17-21.23s8.07-12.13 12.11-20.21 2-15.16-1-21.22-27.25-65.69-37.35-90c-9.83-23.62-19.82-20.42-27.25-20.8-7.06-.35-15.15-.42-23.22-.42s-21.2 3-32.31 15.16-42.4 41.43-42.4 101.06 43.41 117.23 49.47 125.32 85.42 130.44 207 182.91a692.65 692.65 0 0069.06 25.52c29 9.23 55.42 7.92 76.3 4.8 23.27-3.47 71.67-29.3 81.77-57.6s10.09-52.55 7.06-57.6-11.12-8.09-23.24-14.16z"
                  fill-rule="evenodd"
                />
              </svg>
              <span>WhatsApp</span>
            </button>
          </a>
          <!-- </n-link> -->
        </div>
      </div>
    </div>
    <!-- 
    <div class="grid grid-cols-3 gap-4">
      <div>
        <img src="~/assets/images/numago-logo.svg" alt="" />
      </div>
    <div>9</div>
    -->
    <!-- </div> -->
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      email: 'info@numago.nl',
      whatsappLink: ' https://wa.me/message/3Y7D4GVKZSRUO1',
    }
  },
})
</script>

<style lang="postcss" scoped>
.badge {
  @apply inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700;
  &:hover {
    @apply bg-gray-300;
  }
}
._list-item {
  @apply py-1 w-full rounded inline-flex items-center;
}
._block-button {
  @apply font-bold py-3 px-4 w-full rounded inline-flex items-center justify-center mb-3 shadow-lg text-white;
  &._blue-button {
    @apply bg-indigo-500;
    &:hover {
      @apply bg-indigo-600;
    }
  }
  &._green-button {
    background-color: #25d366;
    &:hover {
      background-color: #21bd5b;
    }
  }
}
</style>
