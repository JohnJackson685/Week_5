<template>
  
  <h1>HelloWorld</h1>

  <button @click="button">Click this button</button>
  <p>Click counter: {{clicks}}</p>
  
  <input v-model="email">

  <p> Copy: {{email}}</p>

</template>

<script>

export default {
  
  data() {
    return {
      clicks: 0,
      email: ''
    }
  },

  methods: {
    button() {
      this.clicks++;
    }
  }
}
</script>




