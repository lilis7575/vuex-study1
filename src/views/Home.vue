<template>
  <v-container>
    <h1>Home</h1>
    <h4>모든 유저의 수 : {{ allUsersCount }}</h4>
  </v-container>
</template>
<script>
import { mapGetters } from "vuex";

export default {
  computed: {
    ...mapGetters(["allUsersCount"])
  }
};
</script>