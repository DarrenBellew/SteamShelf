<template>
    <div id="app">
    	<busy-spinner></busy-spinner>
		<img src="./assets/logo.png">
		<router-view></router-view>
		<cover></cover>
    </div>
</template>

<script>
    import BusySpinner from './common/components/busy-spinner.vue';
	import Cover from '@/components/Cover';

    export default {
        name: 'app',
        components: {
			BusySpinner,
			Cover
		}
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
