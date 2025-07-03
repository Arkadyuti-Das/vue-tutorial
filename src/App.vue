<template>
  <div>
    <ul>
      <li v-for="(items, key) in myInfo">{{ key }}: {{ items }}</li>
    </ul>
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