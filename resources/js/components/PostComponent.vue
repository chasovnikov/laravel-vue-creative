<template>
<div>
    <CreateComponent></CreateComponent>
    <SinglePostComponent></SinglePostComponent>
</div>
</template>

<script>
import SinglePostComponent from './SinglePostComponent.vue';
import CreateComponent from './CreateComponent.vue';

export default {
    name: "PostComponent",

    data() {
        return {
            persons: null
        }
    },

    mounted() {
    },

    methods: {
    },

    components: {
        SinglePostComponent,
        CreateComponent
    }
}
</script>

<style scoped>

</style>
