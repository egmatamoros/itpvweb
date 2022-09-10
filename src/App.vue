<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    </v-app-bar>

    <v-main>
        <v-form>
          <v-container>
              <v-col
                cols="12"
                sm="6"
                md="3"
              >
                <v-text-field
                  label="Usuario"
                  solo
                ></v-text-field>
              </v-col>

              <v-col
                cols="12"
                sm="6"
                md="3"
              >
                <v-text-field
                  label="Contraseña"
                  solo
                ></v-text-field>
              </v-col>

              <v-col
                cols="12"
                sm="6"
                md="3"
              >
              <v-row align="center">
            <v-col
              cols="12"
              sm="6"
            >
              <div class="text-center">
      
                <div class="my-2">
                  <v-btn
                    color="blue-ligth"
                    dark
                  >
                    Ingresar
                  </v-btn>
                </div>
              </div>
            </v-col>
          </v-row>
              </v-col>
          </v-container>
        </v-form>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
