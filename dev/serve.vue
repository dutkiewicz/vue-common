<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { V2pCommonSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  V2pCommonSample,
  // }
});
</script>

<template>
  <div id="app">
    <v2p-common-sample />
  </div>
</template>
