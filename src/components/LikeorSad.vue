<template>
  <div class="btn-group">
    <button type="button" class="h1btn-sm btn-outline-success" @click="ilike">
      <!-- <img src="emoji-smile-fill.svg" alt="Like" width="24" height="24" /> -->
      {{ likes }}
      Likes
    </button>
    <button type="button" class="h1btn-sm btn-outline-danger" @click="isad">
      <!-- <img src="emoji-frown-fill.svg" alt="Sad" width="24" height="24" /> -->
      {{ sads }}
      Sad
    </button>
  </div>
</template>
<script setup>
import { ref } from "vue";

let [likes, sads] = [ref(0), ref(0)];
function ilike() {
  return likes.value++;
}
function isad() {
  return sads.value++;
}
</script>
<style scoped></style>
