<template>
  <v-container fluid>
    <v-layout row wrap>
      <v-flex md12 lg4 class="ma-3">
        <v-time-picker v-model="e4"></v-time-picker>
      </v-flex>
      <v-flex md12 lg8 class="ma-3">
        <v-time-picker v-model="e4" landscape></v-time-picker>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
  export default {
    data () {
      return {
        e4: null,
      }
    }
  }
</script>
