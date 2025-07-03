<template>
  <div>
    <template v-for="name in myInfo" :key="name">
      <p v-if="name!=='Apple'">{{ name }}</p>
    </template>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        myInfo: ["Apple", "Mango", "Pineapple"]
      }
    }
  }
</script>

<style lang="css" scoped>

</style>