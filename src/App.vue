<template>
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        <app-header></app-header>
      </div>
    </div>
    <hr>
    <div class="row">
      <app-server></app-server>
      <app-server-status></app-server-status>
    </div>
    <hr>
    <div class="row">
      <div class="col-xs-12">
        <app-footer></app-footer>
      </div>
    </div>
  </div>
</template>

<script>
  import Server from './Server.vue';
  import ServerStatus from './ServerStatus.vue';
  import Header from './Header.vue';
  import Footer from './Footer.vue'

  export default {
    components: {
      'app-header': Header,
      'app-footer': Footer,
      'app-server': Server,
      'app-server-status': ServerStatus
    }
  }
</script>

<style>

</style>
