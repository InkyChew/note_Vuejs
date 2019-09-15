<template lang='pug'>
  .row.mx-0
    .col-2.menu
    .col-4.list
    .col-6.edit
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
    }
  },
  methods: {
  }
}
</script>

<style lang='sass'>
  .col-2.menu
    background-color: $blue
    height: 100vh
  .col-4.list
    background-color: $grey
    height: 100vh
  .col-6.edit
    background-color: $white
    height: 100vh
</style>
