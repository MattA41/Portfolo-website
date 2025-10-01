<template>
  <v-card class="text-center">
    <v-card-title>Project Portfolio</v-card-title>
    <v-card-subtitle
      >I built this website to display some of the project I have worked on 
      throughout my education at Eastern washington university</v-card-subtitle
    >
    <v-card-text class="text-center"
      >This is a clone of a couple of the New York Time word games. <br />We
      wanted to make a version that lets you Practice and play as much as you
      want. <br />
    </v-card-text>

    <v-card-text class="text-center">
      There are two games connections and Wordle
      <br />Click on
      <v-icon>mdi-bullseye-arrow</v-icon> to go to the home page <br />
      On the Game pages you can click on the <v-icon>mdi-help-box</v-icon> to
      see how to play the game
    </v-card-text>
    <div class="d-flex justify-center mt-3 mb-5">
      <v-btn
        variant="flat"
        color="primary"
        @click="router.push('/connectionsPractice')"
        >Play Connections (Work in progress)</v-btn
      >
      <div class="mx-3"></div>
      <v-btn
        variant="flat"
        color="primary"
        @click="router.push('/neverEndingWordle')"
        >Play Wordle</v-btn
      >
    </div>
  </v-card>
</template>
<script setup lang="ts">
const router = useRouter();
</script>
