<template>
  <ButtonCounter></ButtonCounter>
  <ButtonCounter></ButtonCounter>

  <button-counter></button-counter>

  <hr />

  <div style="background-color: orange; padding: 5px">
    This is the root component.
    <ComponentA></ComponentA>
    <ComponentA></ComponentA>
  </div>
</template>

<script setup>
import ButtonCounter from './ButtonCounter.vue'
import ComponentA from '@/ComponentA.vue'
//this component is used as a custom element
// each time you use a button counter, then a new button instance is cerated
// pascal case differenciates components defined by the devloper

</script>

<style scoped></style>