<template>
  <div class="home">
    Welcome !

    <logout-panel></logout-panel>
  </div>
</template>

<script>
import LogoutPanel from '../components/LogoutPanel.vue'
// @ is an alias to /src

export default {
  name: 'Home',
  components: {
    LogoutPanel
  }
}
</script>
