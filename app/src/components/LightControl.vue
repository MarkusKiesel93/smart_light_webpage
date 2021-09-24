<template>
  <v-container>
    <v-row>
      <v-col cols=12>
        <v-card>
          <v-card-title>
            Smart Light Controls
          </v-card-title>
          <v-card-actions>
            <v-row>
              <v-col cols=12>
                <v-text-field>
                  Input
                </v-text-field>
              </v-col>
            </v-row>
            <v-row>
              <v-col cols=12>
                <v-btn
                  color="green"
                >
                  <v-icon>
                    mdi-check
                  </v-icon>
                  Light On
                </v-btn>
                <v-btn
                  color="red"
                >
                  <v-icon>
                    mdi-check
                  </v-icon>
                  Light Off
                </v-btn>
              </v-col>
            </v-row>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols=12>
        <v-card>
          <v-card-title>
            Ambient Light Controls
          </v-card-title>
          <v-card-actions>
            <v-btn
              color="green"
            >
              <v-icon>
                mdi-check
              </v-icon>
              Light On
            </v-btn>
            <v-btn
              color="red"
            >
              <v-icon>
                mdi-check
              </v-icon>
              Light Off
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>

export default {
  name: 'LightControl'
}

</script>
