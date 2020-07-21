<template>
  <v-container
    style="background: #f8f9fa; margin-bottom: 30px; padding-bottom: 30px;"
  >
    <v-card flat color="#F8F9FA">
      <v-card-title class="text-center justify-center py-6">
        <h1 class="font-weight-regular display-1 basil--text">
          Planta for Everyone
        </h1>
      </v-card-title>

      <v-tabs v-model="tab" background-color="transparent" color="green" grow>
        <v-tab>
          Farmers
        </v-tab>
        <v-tab>
          Cooperative
        </v-tab>
        <v-tab>
          Enterprise
        </v-tab>
      </v-tabs>

      <v-tabs-items v-model="tab" style="background: #f8f9fa;">
        <v-tab-item>
          <v-row align="center" justify="center">
            <v-col cols="12" md="2" class="text-center">
              <v-img
                max-width="200"
                src="https://planta.ng/wp-content/uploads/2019/08/farmer1.png"
              />
            </v-col>
            <v-col cols="12" md="10" class="text-center">
              For growers looking to streamline their farm management practices,
              escape from spreadsheets and implement data-driven decision
              making.
            </v-col>
          </v-row>
        </v-tab-item>
        <v-tab-item>
          <v-row align="center" justify="center">
            <v-col cols="12" md="2" class="text-center">
              <v-img
                max-width="200"
                src="https://planta.ng/wp-content/uploads/2019/08/coo.png"
              />
            </v-col>
            <v-col cols="12" md="10" class="text-center">
              Managing farmers in a cooperative is often challenging and
              time-consuming. Planta Farmer Network software lets agricultural
              cooperatives, food sourcing/processing companies, NGOs,
              governments, and others boost their farmer network performance.
              Central registry of all farmers in the cooperative Plan and
              monitor production per farmer, crop and field
            </v-col>
          </v-row>
        </v-tab-item>
        <v-tab-item>
          <v-row align="center" justify="center">
            <v-col cols="12" md="2" class="text-center">
              <v-img
                max-width="200"
                src="https://planta.ng/wp-content/uploads/2019/08/enterp-1.png"
              />
            </v-col>
            <v-col cols="12" md="10" class="text-center">
              Planta Enterprise is a tailor-made solution for advanced growers
              with a need for customization including integrations with
              machinery, equipment and sensors to automate data collection
            </v-col>
          </v-row>
        </v-tab-item>
      </v-tabs-items>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: 'Users',
  data() {
    return {
      tab: null,
      items: ['Farmers', 'Cooperative', 'Enterprise'],
      text: 'We bring farm consultant at your fingertip.',
    }
  },
}
</script>
