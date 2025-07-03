<template>
  <div>
    <p>Result of addition: {{ add(10, 20, 30) }}</p>
    <p>Multiply me: {{ multiply(20) }}</p>
    <p>Multiply me: {{ multiply(baseNum) }}</p>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        baseMultiplier: 5,
        baseNum: 2
      }
    },
    methods: {
      add(n1, n2, n3){
        return n1+n2+n3;
      },
      multiply(num){
        return num*this.baseMultiplier
      }
    }
  }
</script>

<style lang="css" scoped>

</style>