<template>
    <div class="pb-16">
        <v-app-bar title="HOME" color="black">
           <div class="d-none d-md-flex">
            <v-btn to="/">Home</v-btn>
            <v-btn to="/local">About</v-btn>
            <v-btn to="/contact">Contact</v-btn>
           </div>
           <div class="d-md-none pr-5">
            <v-icon onclick="mdi-menu" md-6>mdi-menu</v-icon>
            </div>
        </v-app-bar>
    </div>
</template>

<script setup>

</script>

<style  scoped>

</style>