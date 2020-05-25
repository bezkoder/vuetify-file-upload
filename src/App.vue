<template>
  <v-app>
    <v-container fluid style="width: 600px">
      <div class="mb-5">
        <h1>bezkoder.com</h1>
        <h2>Vuetify File Upload</h2>
      </div>

      <upload-files></upload-files>
    </v-container>
  </v-app>
</template>

<script>
import UploadFiles from "./components/UploadFiles";

export default {
  name: "App",
  components: {
    UploadFiles,
  },
};
</script>
