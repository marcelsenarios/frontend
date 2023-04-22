<template>
    <div class="menu">
        <a href="#categorias">Categorias</a>
        <a href="#produtos">Produtos</a>
    </div>
  </template>
  
  <script>
  export default {
    name: 'MenuComponent'
  }
  </script>
  
  <style scoped>
 .menu {
    width: 100%;
    padding: 10px;
    display: flex;
    flex-direction: row;
    justify-content:flex-start;   
    border-bottom: 1px solid #ccc;
 }
 .menu a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
    margin: 5px;
 }

 .menu a:hover {
   text-decoration: underline;
   color: #ccc;
 }
  </style>
  