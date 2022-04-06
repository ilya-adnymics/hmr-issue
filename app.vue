<template>
  <div>
    <!-- If you change the text below and save, the page will be updated automatically -->
    Counter value from template: 1 <br />
    Counter value from script: {{ counter }}
    <NuxtWelcome />
  </div>
</template>

<script setup>
// If you change the counter value and save, the page is not updated
// You need to refresh to see the new value
const counter = 1;
</script>
