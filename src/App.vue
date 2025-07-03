<template>
  <div>
    <ul>
      <li v-for="(item, index) in names" :key="name">
        {{ item }} has index {{ index }}
      </li>
    </ul>
  </div>
  <div>
    <ul>
      <li v-for="(items, index) in fullNames" :key="items.firstName">
        {{ items.firstName }} {{ items.lastName }}
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        names: ["George", "Frank", "Steven"],
        fullNames: [{
          firstName: "Robert",
          lastName: "Downey"
        }, {
          firstName: "Seth",
          lastName: "Rollins"
        }, {
          firstName: "Thompson",
          lastName: "Alvarez"
        }]
      }
    }
  }
</script>

<style lang="css" scoped>

</style>