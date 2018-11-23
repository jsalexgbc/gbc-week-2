<template>
  <div class="accordion">
    <label class="accordion-header"> {{ title }} </label>
  </div>
</template>

<script>
export default {
  name: "gbc-accordion",
  props: ["title"]
};
</script>
