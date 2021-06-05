<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <div>
    <Hero />
    <WhyLotus />
    <About />
    <Work />
    <Different />
    <Team />
    <Contact />
  </div>
</template>

<script>
import Hero from "../components/Index/Hero.vue";
import WhyLotus from "../components/Index/WhyLotus.vue";
import About from "../components/Index/About.vue";
import Work from "../components/Index/Work.vue";
import Different from "../components/Index/Different.vue";
import Team from "../components/Index/Team";
import Contact from "../components/Index/Contact.vue";

export default {
  components: {
    Hero,
    WhyLotus,
    About,
    Work,
    Different,
    Team,
    Contact,
  },
  setup() {
    return {
      navigation,
    };
  },
};
</script>