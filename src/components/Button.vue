<template>
    <component
        :is="tag"
        v-bind="$attrs">
        <slot></slot>
    </component>
</template>
<style>

</style>
<script>
export default {
    props: {
        tag: { type: String, default: "button" },
    },
}
</script>
