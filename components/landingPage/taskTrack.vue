<template>
  <section class="mt-10">
    <v-container>
      <v-row align="center" justify="center">
        <v-col cols="12" md="5">
          <v-container>
            <p class="display-1 font-weight-regular mb-4">
              Task Track
            </p>
            <p style="color: gray;">
              The task track display a summary of what you are currently working
              on, in terms of farm activities and the progress of all the
              expected task during the farming season.
            </p>
          </v-container>
        </v-col>
        <v-col class="text-center" cols="12" md="6">
          <v-card elevation="10">
            <img
              style="max-width: 100%;"
              src="https://res.cloudinary.com/musbell/image/upload/v1585135482/Screenshot_from_2020-03-04_14-38-24_q9qtl5.png"
            />
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  name: 'TaskTrack',
}
</script>
