<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title>Shindy-E</v-toolbar-title>
      <v-spacer />
      <v-btn>Create Event</v-btn>
    </v-app-bar>
    <v-main>
      <slot />
    </v-main>
  </v-app>
</template>

<static-query>
query {
  metadata {
    siteName,
    siteDescription
  }
}
</static-query>