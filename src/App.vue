<template>
    <div id="app">
        <div id="nav"><router-link to="/">Home</router-link> |</div>
        <router-view />
    </div>
</template>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}
* {
    margin: 0;
    padding: 0;
    list-style: none;
    background-size: cover;
    box-sizing: border-box;
}

#nav {
    padding: 30px;
    background-color: red;
}

#nav a {
    font-weight: bold;
    color: #2c3e50;
}

#nav a.router-link-exact-active {
    color: #42b983;
}
</style>
