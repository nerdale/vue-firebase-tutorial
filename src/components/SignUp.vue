<template>
  <div class="sign-up">
    <p>Let's create a new account</p>
    <input type="text" placeholder="Email">
    <input type="password" placeholder="Password">
    <button>Sign Up</button>
    <span>or go back to <router-link to="/login">login </router-link></span>
  </div>
</template>

<script>
export default {
  name: 'signUp',
  data: function() {
    return {}
  },
  methods: {}
}
</script>

<style scoped>
  .signUp {
    margin-top: 5em;
  }

  input {
    margin: 2em auto;
    width: 20%;
    padding: 1em;
    display: block;
  }

  button {
    margin-top: 2em;
    width: 10%;
    cursor: pointer;
  }

  span {
    display: block;
    margin-top: 2em;
    font-size: 11px;
  }
</style>


