<template>
  <div class="pl-2 lg:w-1/5 w-full">
    <aside
      id="right"
      class="w-full lg:block top-[65px] sticky overflow-y-auto"
      style="max-width: 250px; height: calc(100vh - 80px); min-width: 280px"
    >
      <div id="right-scroll" class="relative text-white pt-3 relative pl-8">
        <div class="absolute h-4 w-1.5 bg-secondary left-0 top-2 z-40"></div>
        <h2 class="uppercase font-bold leading-5 text-sm text-[#e99e9]">
          On this page
        </h2>
        <div class="flex flex-col text-base pl-3 pt-3 leading-5">
          <a
            v-for="(header, i) in $page.headers"
            :key="i"
            :href="`#` + header.slug"
            class="py-1"
            :class="{ '!text-[#0db9e9]': isSlug(`#` + header.slug) }"
            >{{ header.title }}</a
          >
        </div>
      </div>
    </aside>
  </div>
</template>
  
  <script>
export default {
  computed: {},

  methods: {
    isSlug(hash) {
      return this.$route.hash === hash;
    },
  },
};
</script>
  
  <style>
</style>