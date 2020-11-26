<template>
  <v-app>
    <v-content>
      <v-container>
        <v-layout>
          <v-flex>
            <v-card
                class="float-right pa-2"
                color="grey"
                height="600"
                width="400">
              <v-card
                  class="float-left"
                  outlined>
                justify-end
              </v-card>
            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "Login",
  data() {
    return {
      message: '登录界面'
    }
  }
}
</script>

<style scoped>

</style>
