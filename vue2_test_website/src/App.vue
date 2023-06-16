<template>
    <div id="app">
        <img alt="Vue logo" src="./assets/logo.png" />
        <HelloWorld msg="Welcome to Your Vue.js App" />
    </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
    name: 'App',
    components: {
        HelloWorld,
    },
    //   The mounted hook is called after the instance has been mounted, which means the el is replaced by the component’s root element.
    mounted() {
        console.log('App.vue mounted');
    },
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
