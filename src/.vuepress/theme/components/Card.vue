<template>
  <div class="text-white bg-[#1e293b] rounded-lg">
    <div class="w-full">
      <div class="w-full">
        <img :src="image" class="object-cover w-full" alt="" srcset="" />
      </div>
      <div class="p-4">
        <p class="capitalize font-bold text-lg">
          <a :href="link">{{ title }}</a>
        </p>
        <p class="text-md pt-2">
          <slot />
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ["title", "link", "image"],
};
</script>

<style>
</style>