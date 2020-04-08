<template>
  <v-gauge :value="value" :gaugeTitle="false" />
</template>
<script>
  import VGauge from './VGauge';

  export default {
    components: {
      VGauge,
    },
    data() {
      return {
        value: 35,
      };
    },
  };
</script>
