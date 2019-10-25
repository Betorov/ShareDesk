<template>
  <div class="auth">
    <v-container
      class="fill-height"
      fluid
    >
      <v-row
        align="center"
        justify="center"
      >
        <v-col
          cols="12"
          sm="8"
          md="4"
        >
          <v-card
            class="mx-auto"
            max-width="344"
          >
            <h2>Authentication</h2> 
            <v-btn small color="primary">Login</v-btn>
            <br>
            <v-btn small color="primary">Create</v-btn>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  name: 'Authentication',
  methods: {
  
  },
  mounted() {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
