<template>
  <div class="home">
    <HeaderShayna />

    <HeroShayna />

    <WomanHeroShayna />
    
    <InstaShayna />

    <PartnerShayna />

    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomanHeroShayna from '@/components/WomanHeroShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import PartnerShayna from '@/components/PartnerShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';
export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroShayna,
    WomanHeroShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>

<style>
.set-bg{
    width: 100%;
    height: 600px;
}

.banner-info {
    margin-top: 160px;
}
</style>