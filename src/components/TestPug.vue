<template lang="pug">
div
  p(class="bg-red-500") I am written in pug. If you change my class to a new one the JIT has not seen, I will NOT update. The HMR will NOT detect a change in index.css
</template>

<script>
export default {
  name: "test-pug",
};
</script>

