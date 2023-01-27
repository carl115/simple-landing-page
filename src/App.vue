<template>
  <header-landing></header-landing>
  <main>
    <section-one></section-one>
    <section-two></section-two>
    <section-three></section-three>
    <section-four></section-four>
    <section-five></section-five>
    <section-form></section-form>
    <footer-landing></footer-landing>
  </main>
</template>

<script>
import HeaderLanding from "./components/HeaderLanding.vue";
import SectionOne from "./components/SectionOne.vue";
import SectionTwo from "./components/SectionTwo.vue";
import SectionThree from "./components/SectionThree.vue";
import SectionFour from "./components/SectionFour.vue";
import SectionFive from "./components/SectionFive.vue";
import SectionForm from "./components/SectionForm.vue";
import FooterLanding from "./components/FooterLanding.vue";

export default {
  components: {
    HeaderLanding,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    SectionFive,
    SectionForm,
    FooterLanding,
  },
};
</script>
