<template>
<div id="app">
    <h1>{{ msg }}</h1>

    <hr>
    
    <p>// Played with Vuejs...</p>
    <test></test>
    
    <hr>
    
    <p>// Played with discord widgt...</p>
    <iframe src="https://discordapp.com/widget?id=253926765842399232&theme=dark" width="350" height="500" allowtransparency="true" frameborder="0"></iframe>
    
    <hr>
    
    <p>// Played with Webhooks...</p>
    
    </div>
</template>

<script>
    import Test from './components/Test.vue'

    export default {
        name: 'app',
        components: {
            Test
        },
        data () {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
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

    h1, h2 {
        font-weight: normal;
    }

    ul {
        list-style-type: none;
        padding: 0;
    }

    li {
        display: inline-block;
        margin: 0 10px;
    }

    a {
        color: #42b983;
    }
</style>
