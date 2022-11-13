<script>
export default {
  data() {
    return {
      msg: 'This is only test',
      rawHtml: 'rawHtml',
    };
  },
};
</script>

<template>
  <h2>Template Syntax</h2>
  <span>Message: {{ msg }}</span>
  <p>Using text interpolation: {{ rawHtml }}</p>
  <p>Using v-html directive: <span v-html="rawHtml"></span></p>
</template>

<style scoped>
h2 {
  text-decoration: underline;
}
</style>
