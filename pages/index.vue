<template>
  <div class="container mx-auto bg-gray-200">
    <!-- <div class="flex justify-center"></div> -->
    <div class="flex justify-center">
      <div class="max-w-sm rounded overflow-hidden shadow-lg mt-20 bg-white">
        <div class="px-6 py-4">
          <img
            src="~/assets/images/numago-logo.svg"
            alt=""
            class="sm:mt-15 h-20"
          />
          <p class="text-gray-700 text-base mt-4">
            Software Development, IT Consultancy, Online Marketing
          </p>
          <ul class="mt-4">
            <li>E-mail: <a href="mailto:info@numago.nl">info@numago.nl</a></li>
            <li>KVK: 76360601</li>
          </ul>
          <div class="font-bold text-xl mb-2 mt-10 text-center">
            Coming soon..
          </div>
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

<style lang="postcss" scoped>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}*/
.badge {
  @apply inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700;
  &:hover {
    @apply bg-gray-300;
  }
}
</style>
