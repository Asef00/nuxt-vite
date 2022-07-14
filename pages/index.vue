<template>
  <v-runtime-template :template="template">
    <Tutorial />
  </v-runtime-template>
</template>

<script>
import VRuntimeTemplate from "v-runtime-template";

export default {
  name: "IndexPage",

  components: {
    VRuntimeTemplate,
  },

  data() {
    return {
      name: "Mellow",
      template: `<span>Hello {{ name }}!</span>`,
    };
  },
};
</script>
