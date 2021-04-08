<template>
  <div>
    <SliderOne />
    <AboutAgency />
    <BlogHome />
    <CallToAction />
  </div>
</template>

<script>
  import SliderOne from "~/components/home/SliderOne";
  import AboutAgency from "~/components/home/AboutAgency";
  import BlogHome from "~/components/home/BlogHome";
  import CallToAction from "~/components/home/CallToAction";
  export default {
    components: {
      SliderOne,
      AboutAgency,
      BlogHome,
      CallToAction,
    }
  }
</script>
