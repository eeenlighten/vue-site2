<template>
    <HeaderSection fonts="gmarket" />
    <SliderSection />
    <TextSection fonts="gmarket" />
    <CardSection fonts="gmarket" />
    <ImgSection fonts="gmarket" />
    <BannerSection fonts="gmarket" />
    <ReviewSection fonts="gmarket" />
    <FooterSection fonts="gmarket" />
</template>

<script>
  import HeaderSection from "./components/HeaderSection.vue";
  import SliderSection from "./components/SliderSection.vue";
  import TextSection from "./components/TextSection.vue";
  import CardSection from "./components/CardSection.vue";
  import ImgSection from "./components/ImgSection.vue";
  import BannerSection from "./components/BannerSection.vue";
  import ReviewSection from "./components/ReviewSection.vue";
  import FooterSection from "./components/FooterSection.vue";


  export default {
      name: 'App',
      components: {
        HeaderSection,
        SliderSection,
        TextSection,
        CardSection,
        ImgSection,
        BannerSection,
        ReviewSection,
        FooterSection
      }  
}
</script>

<style>
  @import "./App.css";
</style>