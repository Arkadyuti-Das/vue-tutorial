<template>
  <div>
    <p>{{ name }}</p>
    <p>{{ counter }}</p>
  </div>
  <div>
    <button @click="name='King'">Change Name</button>
    <button @click="counter+=1">Increment Counter</button>
    <button @click="counter-=1">Decrement Counter</button>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        name: "Arkadyuti",
        counter: 0
      }
    },
    methods: {
    }
  }
</script>

<style lang="css" scoped>

</style>