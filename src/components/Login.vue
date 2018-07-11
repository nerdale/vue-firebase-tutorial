<template>
  <div class="login">
    <h3>Sign In</h3>
    <input type="text" placeholder="Email">
    <input type="password" placeholder="Password">
    <button>Connection</button>
    <p>You don't have an account? You can <router-link to="/sign-up">create one </router-link></p>
  </div>
</template>

<script>
export default {
  name: 'login',
  data: function() {
    return {}
  },
  methods: {}
}
</script>

<style scoped>
  .login {
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

  p {
    margin-top: 3em;
    font-size: 13px;
  }

  p a {
    text-decoration: underline;
    cursor: pointer;
  }
</style>


