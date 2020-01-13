<template>
  <div class="container">
    <Header/>
    <hr>
    <div class="row">
      <Servers/>
      <ServerDetails/>
    </div>
    <hr>
    <Footer/>
  </div>
</template>

<script>
  import Header from '@/components/Header';
  import Servers from '@/components/Servers';
  import ServerDetails from '@/components/ServerDetails';
  import Footer from '@/components/Footer';

  export default {
    components: { Footer, ServerDetails, Servers, Header }
  };
</script>

<style>

</style>
