<template>
  <v-container fill-height fluid class="constrained-width px-2 px-sm-4">
    <vue-headful
      :title="pageTitle">
    </vue-headful>

    <v-row justify="center" align="center" class="mt-0 mt-sm-2">
      <v-col>
        <center>
          <div class="text-h5">404 Not Found</div>
          <v-btn color="secondary" to="/" class="mt-5">Return to the dashboard</v-btn>
        </center>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component({})
export default class NotFound extends Vue {
  pageName = '404'
}
</script>
