<template>
  <MenuComponent />
  <HomeComponent msg="Sodre Santoro Teste PHP API"/>
  <TableComponent />
</template>

<script>
import HomeComponent from './components/HomeComponent.vue';
import MenuComponent from './components/MenuComponent.vue';
import TableComponent from './components/TableComponent.vue';

export default {
  name: 'App',
  components: {
    HomeComponent,
    MenuComponent,
    TableComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
}
</style>
