<template>
  <v-app>
    <v-app-bar
        color="dark"
        dense
        dark
      >
      <v-spacer></v-spacer>
        <NuxtLink to="/" class="text-decoration-none white--text">Home</NuxtLink>
  
        <v-spacer></v-spacer>
  
        <NuxtLink to="/about" class="text-decoration-none white--text">About</NuxtLink>
  
        <v-spacer></v-spacer>
        <NuxtLink to="/Register" class="text-decoration-none white--text">Register</NuxtLink>
  
        <v-spacer></v-spacer>

        <a class="text-decoration-none white--text">Contact</a>
 
        <v-spacer></v-spacer>
  
      </v-app-bar>
      <v-main>
        <nuxt/>
      </v-main>
  </v-app>

</template>
