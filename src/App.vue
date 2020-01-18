<template>
    <div id="container">
        <h1>{{data}}</h1>
    </div>
</template>
<script>
    export default {
        data() {
            return {
                data:"vue开发环境"
            }
        }
    }
</script>

<style scoped>
    #container {
        color: yellow;
    }
</style>