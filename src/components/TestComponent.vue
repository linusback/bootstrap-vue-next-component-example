<script>
export default {
  name: "TestComponent",
  data: () => {
    return {
      tableItems: [{id:1, name: "Gotrek Gurnisson"},{id: 2, name: "Felis Jaeger"}]
    }
  },
}
</script>

<template>
  <b-card>
    <p>
      some text inside of a card
    </p>
  </b-card>
  <h2>These are some characters from books</h2>
  <b-table :items="tableItems" >

  </b-table>
</template>

<style scoped>

</style>