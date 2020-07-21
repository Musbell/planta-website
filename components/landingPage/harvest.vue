<template>
  <section style="background: #f8f9fa;">
    <v-container>
      <v-row align="center" justify="center">
        <v-col class="text-center" cols="12" md="6">
          <v-card elevation="10" class="mt-10">
            <v-img
              src="https://res.cloudinary.com/musbell/image/upload/v1585135719/Screenshot_from_2020-03-04_14-39-02_hry3zg.png"
            />
          </v-card>
        </v-col>
        <v-col cols="12" md="5">
          <v-container>
            <p class="display-1 font-weight-regular mb-4">
              Harvest Charts
            </p>
            <p style="color: gray;">
              Harvest chart shows the executive the summary of what is the
              harvest is going to be at the end of the season, this gives
              farmers a chance to know what they harvested over time and what
              the possible sales going to be.
            </p>
          </v-container>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  name: 'Harvest',
}
</script>
