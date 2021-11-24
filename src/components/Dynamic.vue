<template>
  <component v-bind:is="view"></component>
</template>

<script>
export default {
  data: () => {
    return {
      view: 'component1'
    }
  },
  components: {
    component1: {
      template: '<h1>HELLO</h1>'
    }
  }
}
</script>
