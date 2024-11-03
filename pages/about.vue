<template>
<v-card
      class="ma-5 pa-5 card-rounded"
      elevation="3"
      >
      <div class="text-center px-16 py-10">
        <h1 class="text-xl-h4">Professor Vuetify Designer</h1>
        <v-card-text>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident eveniet ad voluptas non sapiente inventore excepturi dolorem fuga, veniam aliquid nam, adipisci eos neque rem sint dolor id ex est!</v-card-text>
        <div class="text-center">
      <v-btn
      rounded
      color="primary"
      class="pa-7"
      dark
      >
        Contact me
        <v-icon right>
          mdi-arrow-right
      </v-icon>
        </v-btn>
     </div>
      </div>
      <v-container>
        <v-row>
          <v-col
          cols="12"
          lg="6"
         >
            <v-img
          src="https://framerusercontent.com/images/RRa1bCC6dI2vIaYfsy2uiAe2g.png?scale-down-to=1024"
          aspect-ratio="1.7"
          class="ma-3 img-rounded"
        ></v-img>
          </v-col>
          <v-col
          cols="12"
          lg="6"
         >
            <v-img
          src="https://framerusercontent.com/images/78AvoikXC1uld2FRse5MqtKkQ.png?scale-down-to=1024"
          aspect-ratio="1.7"
          class="ma-3 img-rounded"
        ></v-img>
          </v-col>
        </v-row>
      </v-container>
      </v-card>
  </template>

<style scoped>
.img-rounded {
  border-radius: 20px; /* You can adjust this value to expand the border radius */
}
.card-rounded {
  border-radius: 40px; /* You can adjust this value to expand the border radius */
}
</style>

  