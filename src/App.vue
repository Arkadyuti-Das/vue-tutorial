<template>
  <div>
    <ul>
      <li v-for="(items, index) in hobbies" :key="items.name">
        <p>{{ items.name }}</p>
        <ul>
          <li v-for="item in items.hobby" :key="item">{{ item }}</li>
        </ul>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    data(){
      return {
        hobbies: [{
          name: "Johnson",
          hobby: ["Cooking", "Gardening"]
        }, {
          name: "Mitchell",
          hobby: ["Baking", "Coding"]
        }, {
          name: "Santner",
          hobby: ["Driving", "Playing"]
        }]
      }
    }
  }
</script>

<style lang="css" scoped>

</style>