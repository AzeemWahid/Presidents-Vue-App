<template>
<header>
    <v-app-bar class="navbar" color="purple lighten-3">
        <v-app-bar-nav-icon></v-app-bar-nav-icon>

        <v-toolbar-items>
            <router-link to="/">
            <v-toolbar-title class="link">Home</v-toolbar-title>
            </router-link>
        </v-toolbar-items>

        <v-toolbar-items>
            <router-link to="/about">
                <v-toolbar-title class="link">About</v-toolbar-title>
            </router-link> 
        </v-toolbar-items>

        <v-toolbar-items>
            <router-link to="/tutorial">
                <v-toolbar-title class="link">Tutorial</v-toolbar-title>
            </router-link> 
        </v-toolbar-items>
    </v-app-bar>
</header>
</template>



<script>
export default {
    name: 'HeaderItem'
}
</script>

<style scoped>

.link{
    margin-top: 15px;
    padding-right: 15px;
    text-decoration: none;
}

</style>