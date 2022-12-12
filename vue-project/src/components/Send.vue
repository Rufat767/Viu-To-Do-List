<script setup>
import ListVue from "./List.vue";
</script>
<template>
  <div>
    <h1>To-do list</h1>
    <div class="container input-group mb-3">
      <h2>Write your to-do list: &#9997;</h2>

      <input type="text" v-model="text" />
      <button @click="inp" class="btn btn-danger" type="button" id="button-addon2">
        Add
      </button>
      <ListVue :text="text" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: " ",
    };
  },

  methods: {
    inp() {
      alert("gonder");
    },
  },
};
</script>

<style scoped>
h1 {
  margin: -10px;
  padding: 10px;
  text-align: center;
  color: rgb(55, 119, 172);
}
</style>
