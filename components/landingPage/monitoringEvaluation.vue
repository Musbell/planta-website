<template>
  <section style="background: #f8f9fa;">
    <v-container>
      <v-row align="center" justify="center">
        <v-col class="text-center" cols="12" md="6">
          <v-card elevation="10" class="mt-10">
            <img
              style="max-width: 100%;"
              src="https://res.cloudinary.com/musbell/image/upload/v1585134637/Screenshot_from_2020-03-04_14-39-12_msszrv.png"
            />
          </v-card>
        </v-col>
        <v-col cols="12" md="5">
          <v-container>
            <p class="display-1 font-weight-regular mb-4">
              Monitoring and Evaluation
            </p>
            <p style="color: gray;">
              Planta has the feature of tracking the farm inputs utilization,
              finances/cost of production. Planta Monitoring and evaluations
              allow you to track the expenses of cultivation expenses of
              particular farmland, which also allows the generation production
              cost report over time.
            </p>
          </v-container>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  name: 'MonitoringEvaluation',
}
</script>
