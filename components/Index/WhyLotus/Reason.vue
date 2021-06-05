<template>
  <div
    class="
      relative
      flex flex-col
      min-w-0
      break-words
      bg-white
      w-full
      mb-8
      shadow-lg
      rounded-lg
    "
  >
    <div class="px-4 py-5 flex-auto">
      <div
        class="
          text-white
          p-3
          text-center
          inline-flex
          items-center
          justify-center
          w-12
          h-12
          mb-5
          shadow-lg
          rounded-full
          bg-middle-blue
        "
      >
        <slot name="icon"></slot>
      </div>
      <h6 class="text-xl text-teal-blue font-semibold">{{ title }}</h6>
      <p class="mt-2 mb-4 font-bold text-middle-blue">
        {{ subtitle }}
      </p>
      <p class="mt-2 mb-4">
        {{ body }}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true,
    },
    subtitle: {
      type: String,
      required: true,
    },
    body: {
      type: String,
      required: true,
    },
  },
};
</script>