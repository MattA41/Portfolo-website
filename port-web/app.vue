<template>
  <NuxtLayout>
    <v-app>
      <v-app-bar color="primary">
        <v-app-bar-title>Pentagram</v-app-bar-title>
        <template v-slot:prepend>
          <v-btn icon @click="router.push('/')">
            <v-icon size="x-large">mdi-bullseye-arrow</v-icon>
          </v-btn>
        </template>
      </v-app-bar>
      <v-main>
        <NuxtPage />
      </v-main>
    </v-app>
  </NuxtLayout>
</template>
<script setup lang="ts">
const router = useRouter();
</script>
