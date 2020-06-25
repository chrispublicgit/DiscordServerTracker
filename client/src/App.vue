<template>
    <v-app>
        <v-app-bar app color="blue-grey" dark>
            <router-link to="/" tag="button">DiscordServerTracker</router-link>
            <v-spacer/>
            <router-link to="/about" tag="button">About</router-link>
        </v-app-bar>
        <v-main>
            <v-container>
                <router-view/>
            </v-container>
        </v-main>
        <v-footer app color="blue-grey" class="white--text">
            <span>DiscordServerTracker</span>
            <v-spacer></v-spacer>
            <span>&copy; 2020</span>
        </v-footer>
    </v-app>
</template>

<script>

    export default {
        name: 'App',

        components: {},

        data: () => ({
        }),
    };
</script>
