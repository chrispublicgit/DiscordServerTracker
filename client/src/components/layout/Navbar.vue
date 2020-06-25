<template>
    <v-app-bar app color="blue-grey" dark>
        <router-link to="/" tag="button">DiscordServerTracker</router-link>
        <v-spacer/>
        <router-link to="/about" tag="button">About</router-link>
    </v-app-bar>
</template>

<script>
    export default {
        name: "Navbar"
    }
</script>

<style scoped>

</style>