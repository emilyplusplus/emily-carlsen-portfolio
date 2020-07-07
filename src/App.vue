<template>
  <v-app>
    <v-main>
      <v-container fill-height>
        <v-row align="center" justify="center">
          <v-col class="text-center">
            <h1 class="name">Emily Carlsen</h1>
            <h4 class="subtitle">Coming soon.</h4>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>


export default {
  name: 'App',

  components: {
    
  },

  data: () => ({
    //
  }),
};
</script>

<style lang="scss" scoped>
.v-main {
  background: #b3e5fc;
}
.name {
  font-size: 4em;
}
.subtitle {
  font-size: 1.4em;
}
</style>
