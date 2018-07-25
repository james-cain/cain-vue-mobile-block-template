<template>
  <div class="content-container {{name}}">
      <h1>{{className}}</h1>
  </div>
</template>

<script>

export default {
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
    overflow: auto;
  }

  .{{name}} {

  }
</style>
