<template>
  <aside
    id="sidebar"
    class="w-full hidden w-full lg:block top-[65px] sticky overflow-y-auto border-r-2 border-solid border-[#1e293b]"
    style="max-width: 250px; height: calc(100vh - 80px); min-width: 280px"
  >
    <nav class="px-3">
      <ul id="mainmenu" class="text-white rounded-lg text-lg">
        <li>
          <a
            href="/"
            class="flex items-center gap-3 px-2 py-3 hover:bg-[#1e293b] rounded-lg"
          >
            <div>
              <img
                src="https://docs.deposits.dev/assets/svgs/sidebar/docs_home.svg"
                alt=""
                srcset=""
              />
            </div>
            <p>Docs Home</p>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="flex items-center gap-3 px-2 py-3 hover:bg-[#1e293b] rounded-lg"
          >
            <div>
              <img
                src="https://docs.deposits.dev/assets/svgs/sidebar/api_reference.svg"
                alt=""
                srcset=""
              />
            </div>
            <p>API References</p>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="flex items-center gap-3 px-2 py-3 hover:bg-[#1e293b] rounded-lg"
          >
            <div>
              <img
                src="https://docs.deposits.dev/assets/svgs/sidebar/ui_kit.svg"
                alt=""
                srcset=""
              />
            </div>
            <p>UI Kit</p>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="flex items-center gap-3 px-2 py-3 hover:bg-[#1e293b] rounded-lg"
          >
            <div>
              <img
                src="https://docs.deposits.dev/assets/svgs/sidebar/recipes.svg"
                alt=""
                srcset=""
              />
            </div>
            <p>Guides</p>
          </a>
        </li>

        <li>
          <a
            href="#"
            class="flex items-center gap-3 px-2 py-3 hover:bg-[#1e293b] rounded-lg"
          >
            <div>
              <img
                src="https://docs.deposits.dev/assets/svgs/sidebar/references.svg"
                alt=""
                srcset=""
              />
            </div>
            <p>Glossary</p>
          </a>
        </li>
      </ul>
    </nav>

    <div class="my-8 py-2 text-white">
      <h2 class="uppercase font-bold text-base">Getting Started</h2>
      <div class="flex flex-col text-base">
        <a href="/docs/getting-started/introduction.html" class="py-1"
          >Introduction</a
        >
        <a href="#" class="py-1">Key Terms</a>
        <a href="#" class="py-1">Environments</a>
        <a href="#" class="py-1">Authentication</a>
        <a href="#" class="py-1">Testing</a>
        <a href="#" class="py-1">Errors</a>
      </div>
    </div>

    <div class="my-8 text-white">
      <h2 class="uppercase py-2 font-bold text-base">Services</h2>
      <div class="flex flex-col text-base">
        <a href="/docs/services/email-receipts.html" class="py-1"
          >Email Receipts</a
        >
        <a href="#" class="py-1">Webhooks</a>
      </div>
    </div>

    <div class="my-8 text-white">
      <h2 class="uppercase py-2 font-bold text-base">Libraries & SDKs</h2>
      <div class="flex flex-col text-base">
        <a href="#" class="py-1">E-Commerce</a>
        <a href="#" class="py-1">One-Click Pay</a>
        <a href="#" class="py-1">Payouts</a>
        <a href="#" class="py-1">Balance</a>
      </div>
    </div>

    <div class="text-white">
      <h2 class="uppercase py-2 font-bold text-base">Use Cases</h2>
      <div class="flex flex-col text-base">
        <a href="#" class="py-1">Overview</a>
        <a href="#" class="py-1">Digital Banking</a>
        <a href="#" class="py-1">Invoice Management System</a>
        <a href="#" class="py-1">Donations Engine</a>
        <a href="#" class="py-1">International Remittance</a>
        <a href="#" class="py-1">Challenger Bank</a>
      </div>
    </div>
  </aside>
</template>
  
  <script>
export default {};
</script>
  