<template>
  <div>
    <ul>
      <li v-for="(item, index) in names" :key="name">
        {{ item }} has index {{ index }}
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        names: ["George", "Frank", "Steven"]
      }
    }
  }
</script>

<style lang="css" scoped>

</style>