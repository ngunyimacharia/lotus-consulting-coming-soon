<template>
  <section class="relative py-20">
    <div
      class="
        bottom-auto
        top-0
        left-0
        right-0
        w-full
        absolute
        pointer-events-none
        overflow-hidden
        -mt-20
      "
      style="height: 80px"
    >
      <svg
        class="absolute bottom-0 overflow-hidden"
        xmlns="http://www.w3.org/2000/svg"
        preserveAspectRatio="none"
        version="1.1"
        viewBox="0 0 2560 100"
        x="0"
        y="0"
      >
        <polygon
          class="text-white fill-current"
          points="2560 0 2560 100 0 100"
        ></polygon>
      </svg>
    </div>
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap justify-center text-center mb-24">
        <div class="w-full lg:w-6/12 px-4">
          <h2 class="text-4xl font-semibold text-teal-blue">Our Team</h2>
          <p class="text-lg leading-relaxed m-4 text-blueGray-500">
            Our Team of experts helps our clients understand external trends and
            what they mean to the overall business strategy
          </p>
        </div>
      </div>
      <div class="flex flex-wrap">
        <member
          name="Kamau Wairuri"
          title=" Experienced strategist specialized in advising business & political leaders "
          url="https://www.linkedin.com/in/kamauwairuri/"
        >
          <img
            alt="Kamau Wairuri"
            src="~/assets/images/team/kamau.jpg"
            class="shadow-lg rounded-full max-w-full mx-auto"
            style="max-width: 120px; max-height: 120px"
          />
        </member>
        <member
          name="Veselina Kracheva"
          title="Seasoned manager, expert in strategy, industry insights, economic intelligence"
          url="https://www.linkedin.com/in/veselinakracheva/"
        >
          <img
            alt="Veselina Kracheva"
            src="~/assets/images/team/veselina.jpg"
            class="shadow-lg rounded-full max-w-full mx-auto"
            style="max-width: 120px; max-height: 120px"
          />
        </member>
        <member
          name="Veronica Mwania"
          title="Skilled researcher with over ten years’ experience in field data collection and management"
          url="#"
        >
          <img
            alt="Veronica Mwania"
            src="~/assets/images/team/veronica.png"
            class="shadow-lg rounded-full max-w-full mx-auto"
            style="max-width: 120px; max-height: 120px"
          />
        </member>
        <member
          name="George Mwangi"
          title="Seasoned business manager with good project management & research skills"
          url="https://www.linkedin.com/in/george-mwangi-5a944b3a/"
        >
          <img
            alt="George Mwangi"
            src="~/assets/images/team/george.jpg"
            class="shadow-lg rounded-full max-w-full mx-auto"
            style="max-width: 120px; max-height: 120px"
          />
        </member>
      </div>
    </div>
  </section>
</template>

<script>
import Member from "./Team/Member.vue";

export default {
  components: {
    Member,
  },
};
</script>