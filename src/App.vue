<template>
  <div>
    <template v-for="item in myInfo" :key="item">
      <p>{{ item }}</p>
    <hr>
    </template>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        myInfo: {
          name: "Arkadyuti",
          userId: "cx299",
          domain: "Full Stack"
        }
      }
    }
  }
</script>

<style lang="css" scoped>

</style>