<template>
  <div>
    <Jumbo></Jumbo>
    <!-- Ciao questo è app vue -->
    <Title></Title>
  </div>
</template>

<script>
import Title from './components/AppTitle.vue';

import Jumbo from './components/Jumbo.vue';

export default {
  components: {
    Title,
    Jumbo,
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