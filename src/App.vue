<template>
  <v-app>
    <Layout v-bind:source="`https://github.com`">
      <template v-slot:content>
        <router-view />
      </template>
    </Layout>
  </v-app>
</template>

<script>
import Layout from "@/components/Layout.vue";
export default {
  name: "App",
  components: {
    Layout
  }
};
</script>
