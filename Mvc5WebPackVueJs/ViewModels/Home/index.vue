<template>
    <h1> {{getData() }}aaaaa</h1>
</template>

<script>
    export default {
        name: 'index',
        data() {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        },
        methods: {
            getData: function () {
                var biff = 'biff';
                return biff;
            }
        }
    }
</script>