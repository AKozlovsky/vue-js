<script>
import Guide from './Guide.vue';

const routes = {
  '/guide': Guide,
};
</script>

<template>
  <a href="#/guide">Guide</a>
  <component :is="currentView" />
</template>
