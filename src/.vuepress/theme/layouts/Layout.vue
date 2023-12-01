<template>
  <div class="bg-[#0f172a] h-full">
    <div class="mx-auto h-full px-8 xl:px-0" style="max-width: 1320px">
      <Header />

      <div class="flex pt-20 relative">
        <LeftSidebar />

        <Home v-if="$page.frontmatter.home"></Home>

        <Page :sidebar-items="sidebarItems" v-else />

        <RightSidebar v-if="!$page.frontmatter.home" />
      </div>
    </div>
  </div>
</template>

<script>
import Header from "@theme/components/Header.vue";

import Home from "@theme/components/Home.vue";
import Page from "@theme/components/Page.vue";
import LeftSidebar from "@theme/components/LeftSidebar.vue";
import RightSidebar from "@theme/components/RightSidebar.vue";

export default {
  components: {
    Header,
    Home,
    Page,
    LeftSidebar,
    RightSidebar,
  },

  mounted() {
    console.log();
  },
};
</script>

<style>
</style>