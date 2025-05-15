<template>
  <ion-header>
    <ion-toolbar color="primary">
      <ion-title>Login</ion-title>
    </ion-toolbar>
  </ion-header>

  <ion-content class="ion-padding">
    <ion-text color="primary" class="ion-padding ion-text-center">
      <h1>CMMS mobile</h1>
    </ion-text>

    <ion-card class="ion-padding">
      <!-- Formulário -->
      <ion-list lines="none">
        <!-- Email -->
        <ion-item class="ion-margin-bottom">
          <ion-icon slot="start" name="mail-outline"></ion-icon>
          <ion-input
            type="email"
            placeholder="Email"
            label="Email"
            label-placement="floating"
          ></ion-input>
        </ion-item>

        <!-- Senha -->
        <ion-item class="ion-margin-bottom">
          <ion-icon slot="start" name="lock-closed-outline"></ion-icon>
          <ion-input
            type="password"
            placeholder="Senha"
            label="Senha"
            label-placement="floating"
          ></ion-input>
        </ion-item>
      </ion-list>

      <!-- Botão de Login -->
      <ion-button
        expand="block"
        shape="round"
        class="ion-margin"
        color="primary"
      >
        Entrar
      </ion-button>
    </ion-card>
  </ion-content>
</template>

<script setup lang="ts">
import {
  IonContent,
  IonHeader,
  IonPage,
  IonTitle,
  IonToolbar,
  IonIcon,
} from "@ionic/vue";
import { addIcons } from "ionicons";
</script>

<style scoped>

</style>
