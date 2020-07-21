<template>
  <section style="background: #f2f8eb;">
    <v-container>
      <v-row align="center" justify="center">
        <v-col class="text-center" cols="12">
          <h1 class="display-1 font-weight-medium mt-10">
            Manage your Farm with Planta
          </h1>
          <h4 class="subtitle-1 mt-5">
            The smart farm consultant at your finger tips
          </h4>
          <v-container>
            <v-row align="center" justify="center" class="mt-10">
              <v-col class="text-center" cols="12" md="4">
                <v-icon large>mdi-chart-bar</v-icon>
                <div class="mt-5">
                  <p class="title">Farm Management</p>
                  <p style="color: gray;">
                    Planta farm management software helps you plan, monitor and
                    analyze all activities on your farm easily.
                  </p>
                </div>
              </v-col>
              <v-col class="text-center" cols="12" md="4">
                <v-icon large>mdi-cash-multiple</v-icon>
                <div class="mt-5">
                  <p class="title">Farm Economics</p>
                  <p style="color: gray;">
                    Keep farm financial records and documents in one single
                    place. Track sales, expenses and capital investments and
                    allocate them to each crop production.
                  </p>
                </div>
              </v-col>
              <v-col class="text-center" cols="12" md="4">
                <v-icon large>mdi-bank</v-icon>
                <div class="mt-5">
                  <p class="title">Resource and Inventory</p>
                  <p style="color: gray;">
                    Central registry of employees, seasonal workers, machinery,
                    and fields lets you keep control over your resources.
                  </p>
                </div>
              </v-col>
            </v-row>
          </v-container>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  name: 'Intro',
}
</script>
