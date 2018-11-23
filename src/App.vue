<template>
  <div>
    <gbc-heading title="hello" another="test"></gbc-heading>
    <gbc-heading title="goodbye"></gbc-heading>
    <gbc-button></gbc-button>
    <gbc-accordion title="Accordion 1"></gbc-accordion>
    <gbc-accordion title="Accordion 2"></gbc-accordion>
  </div>
</template>

<script>
import GbcHeading from "./components/heading";
import GbcButton from "./components/button";
import GbcAccordion from "./components/accordion";

export default {
  name: "App",
  components: {
    GbcHeading,
    GbcButton,
    GbcAccordion
  }
};
</script>
