<script setup>
import SendVue from "./components/Send.vue";
import FootherVue from "./components/Foother.vue";
</script>

<template id="full">
<div id="full">
    <h1></h1>
    <SendVue />
    <FootherVue/>

  </div>
</template>



<style>
#full {
  background: rgb(34, 193, 195);
  background: -moz-linear-gradient(
    0deg,
    rgba(34, 193, 195, 1) 0%,
    rgba(253, 187, 45, 1) 100%
  );
  background: -webkit-linear-gradient(
    0deg,
    rgba(34, 193, 195, 1) 0%,
    rgba(253, 187, 45, 1) 100%
  );
  background: linear-gradient(0deg, rgba(34, 193, 195, 1) 0%, rgba(253, 187, 45, 1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#22c1c3",endColorstr="#fdbb2d",GradientType=1);
}
</style>
