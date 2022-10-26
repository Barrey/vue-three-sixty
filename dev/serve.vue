<script>
import Vue from 'vue';
import VueThreeSixty from '@/vue-three-sixty.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueThreeSixty
  }
});
</script>

<template>
  <div id="app360">
    <div style="width:300px;">
      <vue-three-sixty
        :amount="36"
        image-path="https://scaleflex.airstore.io/demo/chair-360-36"
        file-name="chair_{index}.jpg?v2"
        id-element="app360"
      />
    </div>
  </div>
</template>
