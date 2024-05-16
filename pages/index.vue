<template>
    <div>
        <VAppBar>
            <VAppBarTitle>My App</VAppBarTitle>
        </VAppBar>
        <!-- <VNavigation-drawer></VNavigation-drawer> -->
        <v-container fixed>
            <h2>DashBoard</h2>
            <p>Bienvenue sur le dashboard</p>            
        </v-container>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.v-container {
  position: sticky;
  margin-top: 60px; /* Ajuster la valeur en fonction de la hauteur de la barre d'applis */
}
</style>