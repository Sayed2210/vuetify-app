<template>
  <div class="home">
    <v-container>
      <v-row>
        <v-col cols="12" md="4" lg="4" sm="6"
          ><v-row>
            <v-col cols="4">Elsayed</v-col>
            <v-col cols="4">HAssan</v-col>
            <v-col cols="4">Elsayed</v-col>
          </v-row></v-col
        >
        <v-col cols="12" md="4" lg="4" sm="6">Elsayed</v-col>
        <v-col cols="12" md="4" lg="4" sm="6">Elsayed</v-col>
      </v-row>
    </v-container>
    <v-btn color="blue" @click="clickme" :loading="loading"
      >Hey! <v-icon color="white" icon="mdi-arrow-left"></v-icon
    ></v-btn>
    <v-container>
      <v-row>
        <v-col :for="num in 4" :key="num">
          <v-card class="mx-auto" max-width="344">
            <v-img
              src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
              height="200px"
              cover
            ></v-img>

            <v-card-title> Top western road trips </v-card-title>

            <v-card-subtitle> 1,000 miles of wonder </v-card-subtitle>

            <v-card-actions>
              <v-btn color="orange-lighten-2" variant="text"> Explore </v-btn>

              <v-spacer></v-spacer>

              <v-btn
                :icon="show ? 'mdi-chevron-up' : 'mdi-chevron-down'"
                @click="show = !show"
              ></v-btn>
            </v-card-actions>

            <v-expand-transition>
              <div v-show="show">
                <v-divider></v-divider>

                <v-card-text>
                  I'm a thing. But, like most politicians, he promised more than
                  he could deliver. You won't have time for sleeping, soldier,
                  not with all the bed making you'll be doing. Then we'll go
                  with that data file! Hey, you add a one and two zeros to that
                  or we walk! You're going to do his laundry? I've got to find a
                  way to escape.
                </v-card-text>
              </div>
            </v-expand-transition>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script setup>
import { ref } from "vue";
const loading = ref(false);
const clickme = () => {
  loading.value = true;
  setTimeout(() => {
    loading.value = false;
  }, 2000);
};
</script>
