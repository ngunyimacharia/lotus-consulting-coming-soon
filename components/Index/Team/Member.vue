<template>
  <div class="w-full md:w-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
    <div class="px-6">
      <slot />
      <div class="pt-6 text-center">
        <h5 class="text-xl font-bold text-teal-blue">{{ name }}</h5>
        <p class="h-16 m-2 text-sm uppercase font-semibold">
          {{ title }}
        </p>
        <div class="mt-6">
          <a :href="url" target="_blank">
            <button
              class="
                bg-middle-blue
                text-white
                w-8
                h-8
                rounded-full
                outline-none
                focus:outline-none
                mr-1
                mb-1
              "
              type="button"
            >
              <font-awesome-icon :icon="['fab', 'linkedin-in']" />
            </button>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      required: true,
    },
    title: {
      type: String,
      required: true,
    },
    url: {
      type: String,
      required: true,
    },
  },
};
</script>