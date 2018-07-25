<template>
  <div class="content-container {{name}}">
      <h1>{{className}}</h1>
  </div>
</template>

<script>
import BasicContainer from '@vue-materials/basic-container'

export default {
  components: { BasicContainer },
  name: '{{className}}',

  data() {
    return {}
  },

  created() {},

  methods: {}
}

</script>

<style scoped>
  .content-container {
    background: #fff;
    overflow: hidden;
  }

  .{{name}} {

  }
</style>
