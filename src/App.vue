<template>
    <div id="app">
        <!-- <div id="nav"><router-link to="/">Home</router-link> |</div>
        <router-view /> -->
        <Accueil />
    </div>
</template>
<script>
import Accueil from "@/components/Accueil.vue";
export default {
    components: {
        Accueil,
    },
};
</script>
<style>
* {
    margin: 0;
    padding: 0;
    list-style: none;
    background-size: cover;
    box-sizing: border-box;
}
</style>
