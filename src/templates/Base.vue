<template>
    <div>
        <Header/>
        <slot></slot>
    </div>
</template>
<style>

</style>
<script>
import Header from "@/templates/Header.vue"

export default {
    components: {
        Header,
    }
}
</script>
