<template>
  <div class="flex gap-2 text-gray-500 capitalize">
    <p
      v-for="(path, i) in paths"
      :class="{ 'text-white': paths.length - 1 === i }"
      :key="i"
    >
      <span v-if="i !== 0">/</span> <a :href="path.slug"> {{ path.name }} </a>
    </p>
  </div>
</template>
  
  <script>
export default {
  props: ["path"],

  computed: {
    paths() {
      const paths = this.path?.split("/")?.filter((i) => i);

      return paths.map((path) => {
        const pa = path.split("-")?.join(" ");

        if (pa.includes(".html"))
          return { name: pa.split(".html")[0], slug: "#" };

        if (pa === "docs") return { name: "Docs Home", slug: "/" };

        return {
          name: pa,
          slug: `/docs/${path}.html`,
        };
      });
    },
  },
};
</script>
  
  <style>
</style>