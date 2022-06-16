<template>
    <v-container>
      <v-layout wrap style="margin-top:150px;">
        <v-flex sm12 md6 offset-md3>
          <v-card>
            <v-col md="12">
              <v-row>
                <v-col md="12">
                  <v-text-field 
                      label="NIM"
                  >
                  </v-text-field>
                </v-col>
                <v-col>
                  <v-text-field 
                        label="Nama"
                  >
                  </v-text-field>
                </v-col>
              </v-row>
            </v-col>
            <v-col md="12">
              <v-row>
                <v-col md="12">
                  <v-btn block color="primary"
                         
                  >
                    Login
                  </v-btn>
                </v-col>
              </v-row>
            </v-col>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>
</template>