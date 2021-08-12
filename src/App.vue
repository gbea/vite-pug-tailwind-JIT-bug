<template>
  <test-pug></test-pug>
  <test-html></test-html>
</template>

<script>
import TestPug from "./components/TestPug.vue";
import TestHtml from "./components/TestHtml.vue";

export default {
  name: "App",
  components: {
    TestPug,
    TestHtml,
  },
};
</script>

