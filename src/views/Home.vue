<template>
  <div class="home">
    <HeaderHikaru />
    <HeroHikaru />
    <ItemsHikaru />
    <InstagramHikaru />
    <PartnerLogo />
    <FooterHikaru />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderHikaru from "@/components/HeaderHikaru.vue";
import HeroHikaru from "@/components/HeroHikaru.vue";
import ItemsHikaru from "@/components/ItemsHikaru.vue";
import InstagramHikaru from "@/components/InstagramHikaru.vue";
import PartnerLogo from "@/components/PartnerLogo.vue";
import FooterHikaru from "@/components/FooterHikaru.vue";

export default {
  name: "Home",
  components: {
    HeaderHikaru,
    HeroHikaru,
    ItemsHikaru,
    InstagramHikaru,
    PartnerLogo,
    FooterHikaru,

    // HelloWorld,
  },
};
</script>
