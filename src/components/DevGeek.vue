<template>
  <v-container class="fill-height">
    <v-responsive class="d-flex align-center text-center fill-height">
      <v-img contain height="300" src="src/assets/logo.png" />
      <RouterView />

      <div class="py-14" />

      <v-row class="d-flex align-center justify-center">
        <v-col cols="auto">
          <v-btn
            to="/"
            min-width="164"
            rel="noopener noreferrer"
            variant="text"
          >
            <v-icon icon="mdi-home" size="large" start />

            Home
          </v-btn>
        </v-col>

        <v-col cols="auto">
          <v-btn
            href="https://facebook.com/devgeek.dev"
            color="primary"
            min-width="228"
            rel="noopener noreferrer"
            size="x-large"
            target="_blank"
            variant="flat"
          >
            <v-icon icon="mdi-speedometer" size="large" start />

            Facebook
          </v-btn>
        </v-col>

        <v-col cols="auto">
          <v-btn
            to="/about"
            min-width="164"
            rel="noopener noreferrer"
            variant="text"
          >
            <v-icon icon="mdi-account-group" size="large" start />

            About
          </v-btn>
        </v-col>
      </v-row>
    </v-responsive>
  </v-container>
</template>
