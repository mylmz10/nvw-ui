<template>
    <Label class="header" text="Header" :textWrap="true" />
</template>
<script>
export default {
    name: "Header"
}
</script>

<style lang="scss" scoped>
@import '../assets/styles/variables';

.header{
    color: $text-color;
}
</style>
