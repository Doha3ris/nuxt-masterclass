<template>
    <h1>{{ title }}</h1>
</template>

<script>
    export default {
        name: "TopBar",
        props: {
            title: String
        }
    }
</script>

<style scoped>

    h1 {
        color: blue;
    }

</style>