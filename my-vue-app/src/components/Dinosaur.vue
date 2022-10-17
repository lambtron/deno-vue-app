<script>
import { ref } from 'vue'

export default {
  // props: [ 'name', 'description' ]
  props: {
    description: {
      type: String,
      required: true
    }
  },
  inheritAttrs:false

}
</script>


<template>
  {{ this.$route.params.dinosaur }}
  {{ this.$route.params.description }}

</template>