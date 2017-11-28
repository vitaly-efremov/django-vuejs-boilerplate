<template>
    <div id="app">
        <app-title/>
    </div>
</template>

<script>
    import Title from './components/Title.vue';

    export default {
        name: 'app',
        components: {
           'app-title': Title,
        }
    }
</script>
