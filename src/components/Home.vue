<template>
  <div>
    <server-status v-for="server in 5" :key="server"/>
  </div>
</template>

<script>
  import ServerStatus from './ServerStatus';

  export default {
    components: {
      ServerStatus
    }
  };
</script>

<style scoped>

</style>
