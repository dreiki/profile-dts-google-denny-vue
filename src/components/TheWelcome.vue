<script setup>
import WelcomeItem from "./WelcomeItem.vue";
</script>

<template>
  <WelcomeItem>
    <template #heading>Cerita Saya</template>
    Lebih dari empat tahun mengimplementasi infrastruktur networking, storage
    dan server. Selalu beradaptasi dan ingin tahu dengan teknologi baru maupun
    teknologi yang belum pernah dipelajari sebelumnya.
  </WelcomeItem>

  <WelcomeItem>
    <template #heading>Data Diri</template>
    Mari berkoneksi dan mengenal saya lebih dekat dengan mengunjungi halaman
    <a target="_blank" href="https://linkedin.com/in/dreiki">Linked In</a> saya.
  </WelcomeItem>
</template>
