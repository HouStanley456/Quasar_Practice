<template>
  <q-page>
    <section-carousel/>
    <section-cards/>
    <q-page-sticky position="bottom-left" :offset="[18, 18]">
      <q-btn round color="primary" @click="alert" icon="alarm" />
    </q-page-sticky>
  </q-page>
</template>

<script>

import SectionCarousel from './SectionCarousel.vue'
import SectionCards from './SectionCards.vue'
export default {
  components: {
    SectionCarousel,
    SectionCards
  }
}
</script>
