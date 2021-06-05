<template>
  <section class="md:p-36 bg-gray-200 -mt-24">
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap">
        <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
          <reason
            title="Research"
            subtitle="Gain Deeper Insight into Consumer
          Behaviour, Wants and Needs"
            body=" Obtain unique insights into your
          consumers behaviour, expectations and experience with your brand."
          >
            <template slot="icon">
              <svg
                class="w-6 h-6"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                ></path>
              </svg>
            </template>
          </reason>
        </div>
        <div class="w-full md:w-4/12 px-4 text-center">
          <reason
            title="Strategy"
            subtitle="Create and Sustain
Competitive Advantage for your Business"
            body="Whether you are looking to enter a
new market, develop a new product or
grow your business, Lotus will help
you design winning strategies in order to gain or retain competitive advantage."
          >
            <template slot="icon">
              <svg
                class="w-6 h-6"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M16 8v8m-4-5v5m-4-2v2m-2 4h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"
                ></path>
              </svg>
            </template>
          </reason>
        </div>
        <div class="pt-6 w-full md:w-4/12 px-4 text-center">
          <reason
            title="Public Affairs"
            subtitle="Stay abreast of Legislative & Regulatory Developments"
            body="Look to Lotus for interpretation and analysis of the regulatory and legislative landscape, as well as dedicated advocacy to help protect and advance the interests of account-based health plans."
          >
            <template slot="icon">
              <svg
                class="w-6 h-6"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M11 5.882V19.24a1.76 1.76 0 01-3.417.592l-2.147-6.15M18 13a3 3 0 100-6M5.436 13.683A4.001 4.001 0 017 6h1.832c4.1 0 7.625-1.234 9.168-3v14c-1.543-1.766-5.067-3-9.168-3H7a3.988 3.988 0 01-1.564-.317z"
                ></path>
              </svg>
            </template>
          </reason>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import Reason from "./WhyLotus/Reason";

export default {
  components: {
    Reason,
  },
};
</script>