<template>
  <div class="topnav">
    <nuxt-link to='/login'>Log in</nuxt-link>
    <nuxt-link to='/'>Offers</nuxt-link>
    <nuxt-link to='/'>Page1</nuxt-link>
    <nuxt-link to='/'>Page2</nuxt-link>
  </div>
</template>

<style scoped>
  .nav-bar{
    display: flex;
    background-color: #333;
    justify-content: space-between;
  }

  .nav-bar a{
    color:white;
  }

    /* Add a black background color to the top navigation */
  .topnav {
    background-color: #333;
    overflow: hidden;
  }

  /* Style the links inside the navigation bar */
  .topnav a {
    float: left;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
  }

  /* Change the color of links on hover */
  .topnav a:hover {
    background-color: #ddd;
    color: black;
  }

  /* Add a color to the active/current link */
  .topnav a.active {
    background-color: #4CAF50;
    color: white;
  }

</style>
