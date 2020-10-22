<template>
  <div id="app">
      <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand>SuperHero API</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" class="ml-auto" is-nav>
      <b-navbar-nav>
        <b-nav-item><router-link to="/">Home</router-link> </b-nav-item>
        <b-nav-item><router-link to="/about">About</router-link></b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>

    <router-view/>
  </div>
</template>


<style>

a {
  color: white;
}



</style>
