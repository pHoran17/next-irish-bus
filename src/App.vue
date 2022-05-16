<template>
  <header>
      <!-- Basic Top Menu Structure, get working as own component later -->
    <div class="MenuContainer">
        <div class="MenuButton">
            <img src="./assets/menu-regular-24.png">
        </div>
        <div class="searchBar">
            <input type="text" placeholder="Search Route"/>
            <img src="./assets/search-alt-2-regular-24.png" id="searchImage"/>
        </div>
    </div>
  </header>

  <main>
    <!-- Timetables go here-->
    
  </main>
</template>

<script>
  import TopMenu from "./components/TopMenu.vue";
  // Include component + api imports here


</script>

<style>
  .MenuContainer
  {
    padding: 20px;
    background-color: orange;
    width:100%;
    max-width: 1920px;

  }

  .MenuButton
  {
    width:20px;
    height: 20px;
    /* position: relative; */
    display: inline;
    left:0px;
    margin-right: 200px;
  }
  .searchBar
  {
    display: inline;
    position: absolute;
    right:0px;
    width: 400px;
    /* height: 40px; */
    margin-left: 200px;
  }
  #searchImage
  {
    margin-left: 10px;
    margin-right: 10px;
  }
</style>



<!-- <script setup> 
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style>
@import './assets/base.css';

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}

header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}

@media (min-width: 1024px) {
  body {
    display: flex;
    place-items: center;
  }

  #app {
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding: 0 2rem;
  }

  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  .logo {
    margin: 0 2rem 0 0;
  }
}
</style>
-->