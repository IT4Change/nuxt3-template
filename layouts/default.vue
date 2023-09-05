<script setup>


</script>


<template>
    <v-card>
        <v-layout> 
            <div class="main-navigation">
                <NavBar />
            </div>
            <v-main>
                <slot />
            </v-main>
            
            <div id="overlay" />
            <!-- client-only modal -->
            <!-- chat -->
            <v-app-bar
                color="grey-lighten-2"
                flat
                height="48"
                location="bottom"
            >
                <FooterBar />
            </v-app-bar>
            
        </v-layout>
    </v-card>
</template>