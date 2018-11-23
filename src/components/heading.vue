<template>
  <h3>{{ title }} {{ another }}</h3>
</template>

<script>
export default {
  name: "gbc-heading",
  props: ["title", "another"]
};
</script>
