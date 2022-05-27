<script setup>
import Navbar from "../components/navbar.vue";
import { onMounted } from "vue";

onMounted(() => {
  document.getElementsByTagName("body")[0].style.backgroundColor ="#56c5d0"
  document.getElementsByTagName("body")[0].style.backgroundSize ="cover";
});
</script>

<template>
  <main>
    <navbar/>
    <div class = "title">
      <h1> "Bacalah Al-Qur'an mu, agar selamat kehidupan dunia dan akhiratmu." </h1>
    </div>

  </main>
</template>

<style>
.title{
  text-align: center;
  font-family: -apple-system;
}
</style>
