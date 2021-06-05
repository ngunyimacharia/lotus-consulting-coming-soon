<template>
  <Footer>
    <div class="bg-gray-200 pt-2">
      <div
        class="
          md:flex
          pb-5
          px-3
          m-auto
          pt-5
          border-t border-gray-300
          text-gray-800 text-sm
          flex-col
          md:flex-row
          max-w-6xl
        "
      >
        <div class="text-center mt-2">
          © Copyright {{ year }}. All Rights Reserved.
        </div>
        <div
          class="
            md:flex-auto md:flex-row-reverse
            mt-2
            flex-row flex
            justify-center
            md:justify-start
          "
        >
          <a
            href="https://www.linkedin.com/company/lotusconsultinglimited/"
            target="_blank"
          >
            <font-awesome-icon
              :icon="['fab', 'linkedin']"
              size="lg"
              class="mx-1"
            />
          </a>
          <a href="https://www.instagram.com/lotus_consulting/" target="_blank">
            <font-awesome-icon
              :icon="['fab', 'instagram']"
              size="lg"
              class="mx-1"
            />
          </a>
          <a href="https://www.facebook.com/LotusConsultingLtd" target="_blank">
            <font-awesome-icon
              :icon="['fab', 'facebook']"
              size="lg"
              class="mx-1"
            />
          </a>
        </div>
      </div>
    </div>
  </Footer>
</template>

<script>
export default {
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>