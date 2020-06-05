<template>
    <header class="header">
        <div class="header-inner">
            <h1>My-Portfolio</h1>
            自己紹介
        </div>
    </header>
</template>

<style lang="scss" scoped>

.header {
    background-color: $color-gray;
}

.header-inner {
    height: 60px;
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;

    a {
        color: inherit;
    }
}
</style>
