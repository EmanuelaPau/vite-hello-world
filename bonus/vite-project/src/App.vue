<template>
  <div>
    <Jumbo></Jumbo>
    <!-- Ciao questo è app vue -->
    <!-- <Title></Title> -->
    <InfosCard></InfosCard>
    <InfosCard></InfosCard>
    <InfosCard></InfosCard>
  </div>
</template>

<script>
import Title from './components/AppTitle.vue';

import Jumbo from './components/Jumbo.vue';

import InfoCard from './components/InfosCard.vue';
import InfosCard from './components/InfosCard.vue';

export default {
  components: {
    Title,
    Jumbo,
    InfoCard,
    InfosCard
  },
  data() {
    return {

    }
  },
  methods() {

  },
}
</script>

<style></style>