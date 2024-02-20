<script>
export default {
    props: {
        item: Object,
    },
    methods: {
        generateURL(path) {
            return new URL(path, import.meta.url).href;

        }
    },
};
</script>
<template></template>
<style lang="scss"></style>