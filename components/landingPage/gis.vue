<template>
  <section class="mt-10">
    <v-container>
      <v-row align="center" justify="center">
        <v-col cols="12" md="5">
          <v-container class="ma-3">
            <p class="display-1 font-weight-regular mb-4">
              Geographical Information System
            </p>
            <p style="color: gray;">
              Planta is capable of collecting the geographical location of all
              the farms online and offline, with each farm having its latitude
              and longitude and a pointer on the map for easy access and
              identification. Not only the farm geolocation, but it’s also
              linked up the biodata of the farmers that cultivate a particular
              farm at some period of seasons.
            </p>
          </v-container>
        </v-col>
        <v-col class="text-center" cols="12" md="6">
          <v-card elevation="10">
            <img
              style="max-width: 100%;"
              src="https://res.cloudinary.com/musbell/image/upload/v1585133866/Screenshot_from_2020-03-23_16-44-42_obs99k.png"
            />
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  name: 'Gis',
}
</script>
