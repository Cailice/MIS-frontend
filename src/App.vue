<template>
    <v-app>
        <v-content>
            <router-view></router-view>
        </v-content>
        <v-footer color="primary" app>
            <span class="white--text">&copy; 2019</span>
        </v-footer>
    </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';
// import Login from './views/Login'

export default {
    name: "App",

    // components: {
    //   Login,
    // },

    data: () => ({
        //
    })
};
</script>
