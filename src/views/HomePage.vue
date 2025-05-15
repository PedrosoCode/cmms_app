<template>
  <ion-header>
    <ion-toolbar color="primary">
      <ion-title>Home</ion-title>
    </ion-toolbar>
  </ion-header>

  <ion-content class="ion-padding">
    <ion-text color="primary" class="ion-padding ion-text-center">
      <h1>a</h1>
    </ion-text>

    <ion-button @click="() => router.push('/Login')">Voltar a login</ion-button>
    <ion-button router-link="/page2" router-direction="back" :router-animation="myAnimation">Click Me</ion-button>
  </ion-content>
</template>

<script setup lang="ts">
import {
  IonContent,
  IonHeader,
  IonPage,
  IonTitle,
  IonToolbar,
  IonIcon
} from "@ionic/vue";
import { addIcons } from "ionicons";
import { useRouter } from 'vue-router';

const router = useRouter();

</script>

    

<style scoped>

</style>
