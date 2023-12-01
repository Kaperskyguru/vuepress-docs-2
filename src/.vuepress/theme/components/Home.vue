<template>
  <main
    class="flex-1 h-full lg:px-8 px-0 pb-8"
    style="max-width: cal(100% - 280px)"
  >
    <div class="text-white">
      <h1 class="text-4xl font-bold py-3">Documentation</h1>
      <p>Welcome to the Deposits documentation!</p>
    </div>
    <section>
      <div class="grid-3">
        <Card
          link="#"
          title="Getting started"
          image="https://docs.deposits.dev/assets/svgs/home/services_dark.svg"
          >Everything you need to get started with Deposits.</Card
        >

        <Card
          link="#"
          title="API Reference"
          image="https://docs.deposits.dev/assets/svgs/home/services_dark.svg"
          >Complete reference documentation for Deposits APIs.</Card
        >

        <Card
          link="#"
          title="Recipes"
          image="https://docs.deposits.dev/assets/svgs/home/services_dark.svg"
          >Quick guides to help you build fast.</Card
        >
      </div>
    </section>
    <section>
      <div class="text-white">
        <h1 class="text-4xl font-bold py-3">Explore our APIs</h1>
        <p>Integrate and build with our suite of APIs</p>
      </div>

      <div class="grid-3">
        <SimpleCard
          image="https://docs.deposits.dev/assets/svgs/home/bank_xs_dark.svg"
          link="#"
          title="Getting started"
        >
          Everything you need to get started with Deposits.</SimpleCard
        >

        <SimpleCard
          image="https://docs.deposits.dev/assets/svgs/home/bank_xs_dark.svg"
          link="#"
          title="Cards"
        >
          Virtual and physical card management.</SimpleCard
        >

        <SimpleCard
          image="https://docs.deposits.dev/assets/svgs/home/bank_xs_dark.svg"
          link="#"
          title="Invoice"
        >
          Invoice creation, distribution and payment management.</SimpleCard
        >

        <SimpleCard
          image="https://docs.deposits.dev/assets/svgs/home/bank_xs_dark.svg"
          link="#"
          title="Wallet"
        >
          Closed or open loop multicurrency wallets.</SimpleCard
        >
      </div>
    </section>

    <section>
      <div class="text-white">
        <h1 class="text-4xl font-bold py-3">
          Quick recipes to have you up and running
        </h1>
        <p>Quick start with easy to use guides.</p>
      </div>

      <div class="grid-2">
        <BigCard
          image="https://docs.deposits.dev/assets/svgs/home/donations_use_case_dark.svg"
          link="#"
          >Donations use case</BigCard
        >

        <BigCard
          image="https://docs.deposits.dev/assets/svgs/home/invoice_management_system_dark.svg"
          link="#"
          >Invoice management system</BigCard
        >
      </div>
    </section>
  </main>
</template>
  
  <script>
import Card from "@theme/components/Card.vue";
import SimpleCard from "@theme/components/SimpleCard.vue";
import BigCard from "@theme/components/BigCard.vue";
export default {
  components: { SimpleCard, Card, BigCard },
};
</script>
  
  <style>
</style>