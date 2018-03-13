<template>
  <v-ons-page>
    <v-ons-toolbar>
      <div class="center">Text input</div>
    </v-ons-toolbar>

    <v-ons-input placeholder="Input your name" float v-model="name">
    </v-ons-input>
  </v-ons-page>
</template>

<script>
export default {
    data() {
        return {
            name: '',
            spdOpen: false,
            shareItems: {
                Twitter: 'md-twitter',
                Facebook: 'md-facebook',
                'Google+': 'md-google-plus'
            }
        }
    }
}
</script>

<style scoped>
.button-margin {
    margin: 6px 0;
}
</style>
