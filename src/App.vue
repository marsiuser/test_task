<template>
  <div id="app">
  <div class="page-container">
    <Header />
    <md-app>
      <md-app-toolbar class="md-primary">
        <span class="md-title">Detailed user information</span>
      </md-app-toolbar>
      <md-app-drawer md-permanent="full">
        <Navbar />
      </md-app-drawer>
      <md-app-content>
          <MainContent />
      </md-app-content>
    </md-app>
  </div>
    <!-- <router-view /> -->
  </div>
</template>

<style lang="scss">
 .md-app {
    max-height: 400px;
    border: 1px solid rgba(#000, .12);
  }
  .md-drawer {
    width: 230px;
    max-width: calc(100vw - 125px);
  }
  .md-app{
    border: none;
  }
  .md-elevation-4{
    box-shadow: none;
    position: sticky;
    color: #fff;
    background-color: blue;
  }
  .md-card-header:last-child{
    margin-bottom: 0px;
  }
</style>

<script>
export default {
  name: 'Normal',
  components: {
    Header: () => import('./components/Header.vue'),
    MainContent: () => import('./components/MainContent.vue'),
    Navbar: () => import('./components/Navbar.vue')
  }
}
</script>