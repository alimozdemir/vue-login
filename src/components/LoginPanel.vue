<template>
  <div>
    <button @click="login">Login</button>
  </div>
</template>

<script>
export default {
  methods: {
    login() {
      localStorage.setItem('token', 'myToken');
      this.$router.push('/')
    }
  }
}
</script>