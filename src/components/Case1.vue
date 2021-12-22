<template lang="pug">
div
  h3 [Pug template]: 
  div(:title="row['item1']") {{ row['item1'] }}
  input(v-model="row['item1']")

  div(:title='row["item2"]') {{ row["item2"] }}
  //- input(v-model='row["item2"]')
</template>

<script>
export default {
  data() {
    return {
      row: {
        item1: "1. Double quotes outside, single quotes inside",
        item2: "2. Single quotes outside, double quotes inside",
      },
    };
  },
};
</script>

<style>
</style>
