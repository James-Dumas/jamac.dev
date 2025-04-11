<template>
    <div class="container-box">
        <slot></slot>
    </div>
</template>

<style scoped lang="scss">
.container-box {
    width: calc(100% - $box-padding * 2 - $box-border-width * 2);
    height: calc(100% - $box-padding * 2 - $box-border-width * 2);
    padding: $box-padding;
    border: $box-border-width solid $text-color;
    border-radius: $box-border-radius;
}
</style>