<template>
  <header
    class="fixed flex justify-center w-full top-0 left-0 mb-[80px] z-50 px-4"
  >
    <nav
      class="flex w-full items-center justify-between bg-[#0f172a] text-white p-3 border-solid border-[#1e293b] border-b"
      style="max-width: 1320px"
    >
      <!-- Logo -->
      <div class="w-32">Logo</div>
      <!-- Search -->
      <div
        class="flex-1 bg-[#0f172a] flex justify-center mx-5 bg-[#1e293b] rounded-md"
      >
        <SearchBox />
      </div>
      <div class="justify-between gap-10 items-center hidden lg:flex">
        <div>v0.0.0</div>
        <div>Icon</div>
        <div><a href="https://github.com">Github</a></div>
        <div>
          <button class="bg-[#0db9e9] px-4 py-2 rounded-md text-[#212934]">
            Submit a request
          </button>
        </div>
        <div>
          <button
            class="border-[#0db9e9] border border-outline px-4 py-2 rounded-md text-[#0db9e9]"
          >
            Sign in
          </button>
        </div>
      </div>

      <div class="lg:hidden block" onclick="openSidebar()">
        <svg
          focusable="false"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M3 5H20.359M3 18.186H20.359M3 11.592H20.359"
            stroke="currentcolor"
            stroke-width="1.5"
            stroke-linecap="round"
            stroke-linejoin="round"
          ></path>
        </svg>
      </div>
    </nav>
  </header>
</template>

<script>
import SearchBox from "@SearchBox";
export default {
  components: {
    SearchBox,
  },
};
</script>

<style>
@media (min-width: 1024px) {
  .search-box input {
    display: flex !important;
  }
}

.search-box {
  width: 100%;
}

.search-box input {
  padding-left: 1.25rem;
  padding-right: 1.25rem;
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
  border-style: solid;
  border: none !important;
  width: 100%;
  display: "none";
  border-radius: 0.375rem;
  background: #1e293b;
}
</style>