<template>
    <section class="header-app">
        <slot></slot>
    </section>
</template>

<script>
export default {
    data(){
        return {

        }
    }
}
</script>
<style lang="css" scoped>
.header-app{
    height: 60px;
    box-shadow: 0px 3px 6px #00000029;
}
</style>