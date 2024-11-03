<template>
  <v-card
  class="ma-4"
  elevation="2"
>
<v-form  @submit.prevent="submit">
    <v-container>
      <v-row>
        <v-col
          cols="12"
          sm="6"
        >
          <v-text-field
            label="First Name"
            filled
            required
          ></v-text-field>
        </v-col>

        <v-col
          cols="12"
          sm="6"
        >
          <v-text-field
            label="Last Name"
            filled
            required
          ></v-text-field>
        </v-col>
        <v-col
          cols="12"
          sm="6"
        >
          <v-text-field
            label="Email"
            filled
            required
          ></v-text-field>
        </v-col>
        <v-col
          cols="12"
          sm="6"
        >
          <v-text-field
            label="Password"
            filled
            required
          ></v-text-field>
        </v-col>
        <v-col
        cols="12"
          sm="6">
          <v-btn
      class="blue"
      @click="submit"
    >
      Register
    </v-btn>
        </v-col>
      </v-row>
    </v-container>
  </v-form>
</v-card>
</template>

<script>
  export default {
    methods: {
      submit () {
        this.$refs.observer.validate()
      },
    },
  }
</script>
