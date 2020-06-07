<template>
    <header class="header">
        <div class="header-inner">
            <nuxt-link to="/about">
            自己紹介
            </nuxt-link>
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
    font-size: 15px;

}
</style>
