<template>
    <v-app>
        <Navbar/>
        <v-main>
            <v-container>
                <router-view/>
            </v-container>
        </v-main>
        <Footer/>
    </v-app>
</template>

<script>

    import Footer from "@/components/layout/Footer";
    import Navbar from "@/components/layout/Navbar";
    export default {
        name: 'App',

        components: {Navbar, Footer},

        data: () => ({
        }),
    };
</script>
