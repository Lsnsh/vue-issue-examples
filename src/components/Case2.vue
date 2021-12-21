<template>
  <div>
    <h3>[HTML template]: </h3>
    <div :title="row['item1']">{{row['item1']}}</div>
    <input v-model="row['item1']" type="text">

    <div :title='row["item2"]'>{{row["item2"]}}</div>
    <input v-model='row["item2"]' type="text">
  </div>
</template>

<script>
export default {
  data() {
    return {
      row: {
        item1: "1. Double quotes outside, single quotes inside",
        item2: "2. Single quotes outside, double quotes inside",
      }
    }
  }
}
</script>

<style>
</style>
