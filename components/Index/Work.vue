<template>
  <!-- This example requires Tailwind CSS v2.0+ -->
  <div class="py-12 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="lg:text-center">
        <p
          class="
            mt-2
            text-3xl
            leading-8
            font-extrabold
            tracking-tight
            text-teal-blue
            sm:text-4xl
          "
        >
          How We Work
        </p>
        <p class="mt-4 max-w-2xl text-xl text-gray-500 lg:mx-auto">
          We recognize that research and strategy are hard to get right but the
          way we work ensures that we provide you with simply the best output
          possible. Though each assignment is different, our work generally
          follows four main steps.
        </p>
      </div>

      <div class="mt-10">
        <dl
          class="
            space-y-10
            md:space-y-0
            md:grid md:grid-cols-2
            md:gap-x-8 md:gap-y-10
          "
        >
          <div class="relative">
            <dt>
              <div
                class="
                  absolute
                  flex
                  items-center
                  justify-center
                  h-12
                  w-12
                  rounded-md
                  bg-middle-blue
                  text-white
                "
              >
                <!-- Heroicon name: outline/globe-alt -->
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
                    d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z"
                  ></path>
                </svg>
              </div>
              <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                Understand
              </p>
            </dt>
            <dd class="mt-2 ml-16 text-base text-gray-500">
              We first engage with you to ensure we get a good understanding of
              the challenge you are trying to solve.
            </dd>
          </div>

          <div class="relative">
            <dt>
              <div
                class="
                  absolute
                  flex
                  items-center
                  justify-center
                  h-12
                  w-12
                  rounded-md
                  bg-middle-blue
                  text-white
                "
              >
                <!-- Heroicon name: outline/scale -->
                <svg
                  class="h-6 w-6"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M3 6l3 1m0 0l-3 9a5.002 5.002 0 006.001 0M6 7l3 9M6 7l6-2m6 2l3-1m-3 1l-3 9a5.002 5.002 0 006.001 0M18 7l3 9m-3-9l-6-2m0-2v2m0 16V5m0 16H9m3 0h3"
                  />
                </svg>
              </div>
              <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                Plan
              </p>
            </dt>
            <dd class="mt-2 ml-16 text-base text-gray-500">
              We then plan step by step, making the necessary notes, how we are
              going to tackle the assignment.
            </dd>
          </div>

          <div class="relative">
            <dt>
              <div
                class="
                  absolute
                  flex
                  items-center
                  justify-center
                  h-12
                  w-12
                  rounded-md
                  bg-middle-blue
                  text-white
                "
              >
                <!-- Heroicon name: outline/lightning-bolt -->
                <svg
                  class="h-6 w-6"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  aria-hidden="true"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M13 10V3L4 14h7v7l9-11h-7z"
                  />
                </svg>
              </div>
              <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                Do
              </p>
            </dt>
            <dd class="mt-2 ml-16 text-base text-gray-500">
              We execute the plan- collecting data and analysing it- as
              discussed with you. We keep you updated.
            </dd>
          </div>

          <div class="relative">
            <dt>
              <div
                class="
                  absolute
                  flex
                  items-center
                  justify-center
                  h-12
                  w-12
                  rounded-md
                  bg-middle-blue
                  text-white
                "
              >
                <!-- Heroicon name: outline/annotation -->
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
                    d="M9 17V7m0 10a2 2 0 01-2 2H5a2 2 0 01-2-2V7a2 2 0 012-2h2a2 2 0 012 2m0 10a2 2 0 002 2h2a2 2 0 002-2M9 7a2 2 0 012-2h2a2 2 0 012 2m0 10V7m0 10a2 2 0 002 2h2a2 2 0 002-2V7a2 2 0 00-2-2h-2a2 2 0 00-2 2"
                  ></path>
                </svg>
              </div>
              <p class="ml-16 text-lg leading-6 font-medium text-gray-900">
                Present
              </p>
            </dt>
            <dd class="mt-2 ml-16 text-base text-gray-500">
              We present the findings with you in the agreed format and make any
              necessary amendments as required.
            </dd>
          </div>
        </dl>
      </div>
    </div>
  </div>
</template>