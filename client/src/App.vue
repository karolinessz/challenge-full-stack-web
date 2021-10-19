<template>
<v-app id="app">
  <router-view />
</v-app>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  text-align: center;
  background: #E9E9E9;
}

html {
  overflow-y: auto
}

.no-uppercase {
  text-transform: none !important;
  letter-spacing: 0em !important;
}
</style>
