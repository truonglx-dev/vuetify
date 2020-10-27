<template>
  <div>
    <v-row justify="space-between" class="pa-3">
      <v-btn text> <v-icon>mdi-chevron-left</v-icon>Back </v-btn>
      <v-btn text width="auto">
        <v-icon>
          mdi-chevron-right
        </v-icon>
      </v-btn>
    </v-row>
    <v-row class="pt-4 d-flex flex-column text-center block-title">
      <div class="title pb-4">Card Type</div>
      <div class="sub-title">
        Choose the type of card to add PayInde
      </div>
    </v-row>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
  }
}
</script>

<style scoped lang="scss">
.block-title {
  .title {
    font-weight: bold;
    font-size: 24px;
    line-height: 16px;
  }
  .sub-title {
    font-size: 14px;
    line-height: 16px;
  }
}
</style>
