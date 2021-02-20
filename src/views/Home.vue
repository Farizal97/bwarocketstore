
<template>
  <div class="home">
    <HeaderRocket />
    <HeroRocket />
     <WomanRocket />
     <InstaRocket />
     <PartnerRocket />
     <FooterRocket />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderRocket from "@/components/HeaderRocket.vue";
import HeroRocket from "@/components/HeroRocket.vue";
import WomanRocket from "@/components/WomanRocket.vue";
import InstaRocket from "@/components/InstaRocket.vue";
import PartnerRocket from "@/components/PartnerRocket.vue";
import FooterRocket from "@/components/FooterRocket.vue";



export default {
  name: "home",
  components: {
    HeaderRocket,
    HeroRocket,
    WomanRocket,
    InstaRocket,
    PartnerRocket,
    FooterRocket
  }
};
</script>
