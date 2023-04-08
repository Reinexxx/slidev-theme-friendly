<template>
  <div class="slidev-layout presenter">
    <div class="flex items-center">
      <div class="w-1/2">
        <slot />
      </div>
      <figure class="flex justify-center w-1/2">
        <img
          :src="$attrs.presenterImage || 'https://avatars.githubusercontent.com/u/72688302?v=4'"
          class="bg-gray-500 rounded-full object-cover h-80 w-80 border border-5 border-secondary-400 z-10"
        />
      </figure>
    </div>
  </div>
</template>