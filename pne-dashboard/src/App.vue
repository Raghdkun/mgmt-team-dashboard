<script setup>
import  CardView  from './components/card/CardView.vue'
</script>

<template>
<CardView></CardView>

</template>

<script>
export default {
  components : {
    CardView
  },
  data() {
    return {
      list: [
        {name: 'alen', position: 'GM'},
        {name: 'emma', position: 'GM'},

      ]
    }
  },
}
</script>

<style scoped>

</style>
