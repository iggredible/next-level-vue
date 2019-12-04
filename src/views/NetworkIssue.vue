<template>
  <div>
    <h1>Uh oh!</h1>
    <h3>Looks like you are experiencing network issues</h3>
    <router-link :to="{ name: 'event-list' }"
      >Back to the home page</router-link
    >
  </div>
</template>

<script>
export default {}
</script>

<style></style>
