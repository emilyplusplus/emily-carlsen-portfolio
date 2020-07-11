<template>
  <v-app>
    <v-main>
      <v-container fill-height>
        <v-row align="center" justify="center">
          <v-col class="text-center">
            <v-img class="elevation-0 mx-auto" width="256" src="@/assets/emily.png"></v-img>
            <v-divider class="mx-auto" style="width: 600px;"></v-divider>
            <h1 class="name">Emily Carlsen</h1>
            <v-row>
              <v-col class="text-center">
                <v-btn target="_blank" href="https://twitter.com/emilyplusplus" icon><v-icon>mdi-twitter</v-icon></v-btn>
                <v-btn target="_blank" href="https://www.instagram.com/emilyplusplus/" icon><v-icon>mdi-instagram</v-icon></v-btn>
                <v-btn target="_blank" href="https://github.com/emilyplusplus" icon><v-icon>mdi-github</v-icon></v-btn>
                <v-btn target="_blank" href="https://www.youtube.com/channel/UChoXabQMSsYA8JRbZ_St65Q" icon><v-icon>mdi-youtube</v-icon></v-btn>
                <v-btn target="_blank" href="https://www.linkedin.com/in/emilyplusplus/" icon><v-icon>mdi-linkedin</v-icon></v-btn>
                <v-btn target="_blank" href="https://repl.it/@EmilyCarlsen" icon><v-icon>mdi-code-braces-box</v-icon></v-btn>

              </v-col>
            </v-row>
            <v-row>
              <v-col class="text-center">
                <b>Projects</b><br /><br />
                <a target="_blank" href="https://jsoninspect.com">jsoninspect.com</a><br />
                <a target="_blank" href="https://emilydiy.com">emiydiy.com</a><br />
                ---<br />
                <a target="_blank" href="https://emilyplusplus.wordpress.com">emilyplusplus.wordpress.com</a>
              </v-col>
            </v-row>
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
  background: #f5f5f5;
}
.name {
  font-size: 3em;
  color: #212121;
}
</style>
