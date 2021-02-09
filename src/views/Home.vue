<template>
  <div class="home">
    <HeaderStore />
    <HeroSection/>
    <BannerSection/>
    <InstaStore/>
    <PartnersLogo/>
    <FooterStore/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderStore from "@/components/HeaderStore.vue";
import HeroSection from "@/components/HeroSection.vue";
import BannerSection from "@/components/BannerSection.vue";
import InstaStore from "@/components/InstaStore.vue";
import PartnersLogo from "@/components/PartnersLogo.vue";
import FooterStore from "@/components/FooterStore.vue";

export default {
  name: "Home",
  components: {
    HeaderStore,
    HeroSection,
    BannerSection,
    InstaStore,
    PartnersLogo,
    FooterStore
  },
};
</script>
