<template>
  <div class="text-white bg-[#1e293b] rounded-lg">
    <div id="nohover" href="#" class="p-4">
      <a :href="link">
        <div class="flex justify-between">
          <p class="capitalize font-bold text-lg">{{ title }}</p>
          <img :src="image" alt="" />
        </div>
        <p class="text-md pt-2 hover:text-white">
          <slot />
        </p>
      </a>
    </div>
  </div>
</template>

<script>
export default { props: ["title", "link", "image"] };
</script>

<style>
</style>