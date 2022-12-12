<template>
  <div class="container">
    <div class="py-3" v-for="item of 7" :key="item">
  <ol class="list-group list-group ">
    <!-- <ol class="list-group list-group-numbered"> -->

      <li class="list-group-item">{{text}}</li>
    </ol>
</div>
  </div>
</template>



<script>
export default {
  props : ['text']
}
</script>
