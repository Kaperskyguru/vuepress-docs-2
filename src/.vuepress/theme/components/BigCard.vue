<template>
  <div class="text-white bg-[#1e293b] rounded-lg">
    <div>
      <div class="w-full">
        <img
          src="https://docs.deposits.dev/assets/svgs/home/donations_use_case_dark.svg"
          class="w-full"
          alt=""
          srcset=""
        />
      </div>
      <div class="p-4">
        <p class="capitalize font-bold text-lg">
          <a href="#"> <slot /></a>
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