<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6> </v-flex>
  </v-layout>
</template>

<script>
export default {
sockets:{
  connect(){
    console.log('Client IO connected');
  }
}
};
</script>
