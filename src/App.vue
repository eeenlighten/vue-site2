<template>
    <HeaderSection fonts="gmarket"/>
    <SliderSection />
    <TextSection />
    <CardSection />
</template>

<script>
  import HeaderSection from "./components/HeaderSection.vue";
  import SliderSection from "./components/SliderSection.vue";
  import TextSection from "./components/TextSection.vue";
  import CardSection from "./components/CardSection.vue";


  export default {
      name: 'App',
      components: {
        HeaderSection,
        SliderSection,
        TextSection,
        CardSection
      }  
}
</script>

<style>
  @import "./App.css";
</style>