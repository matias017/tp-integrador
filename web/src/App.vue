<template>
    <div id="app">
        <the-header></the-header>
        <main class="main">
            <router-view></router-view>
        </main>
        <footer class="footer"></footer>
    </div>
</template>

<script>
import TheHeader from './components/TheHeader'

export default {
    name: 'App',
    components: {
        TheHeader
    }
}
</script>

<style>
:root {
  --primary-color: rgb(17, 0, 95);
  --secondary-color: rgb(243, 233, 179);
  --text-shadow-hover: 0 0 4px rgb(97, 97, 97);
}

#app {
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}
</style>
