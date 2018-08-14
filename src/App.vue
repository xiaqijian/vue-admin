<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App',
  mounted() {
    console.log(8888888888)
    window.localStorage.setItem('mame', '2222');
    window.localStorage.setItem("username", "John");
  },
}
</script>
