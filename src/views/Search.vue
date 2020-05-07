<template>
  <div class="search container">
  <Fruit />
  </div>
</template>

<script>
// @ is an alias to /src
import Fruit from '@/components/Fruit.vue'

export default {
  name: 'Search',
  components: {
    Fruit
  }
}
</script>
