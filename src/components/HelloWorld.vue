<template>
  <div>
    <span>First Name</span>
    <input type="text" v-model="firstname" />
    <span>Last Name</span>
    <input type="text" v-model="lastname" />
    <div>
      <h1>{{ firstname }} {{ lastname }}</h1>
    </div>
  </div>
</template>
<script>
export default {
  data: () => {
    return {
      firstname: 'Puffer',
      lastname: 'Dev'
    }
  }
}
</script>



// <template>
//   <component v-bind:is="view"></component>
// </template>

// <script>
// export default {
//   data: () => {
//     return {
//       view: 'component1'
//     }
//   },
//   components: {
//     component1: {
//       template: '<h1>HELLO</h1>'
//     }
//   }
// }
// </script>

