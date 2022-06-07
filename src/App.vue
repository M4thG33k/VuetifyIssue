<template>
  <v-app>
    <v-main>
      <InputWithAppend/>
    </v-main>
  </v-app>
</template>

<script>
import InputWithAppend from "./components/InputWithAppend.vue";

export default {
  name: 'App',

  components: {
    InputWithAppend,
  },
}
</script>
