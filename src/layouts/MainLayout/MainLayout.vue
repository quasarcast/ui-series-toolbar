<script setup>
import MainHeader from './MainHeader.vue'
</script>

<template>
  <q-layout view="lHh Lpr lFf">
    <MainHeader />

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>
