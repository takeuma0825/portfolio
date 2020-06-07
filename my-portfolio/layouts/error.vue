<template>
    <div class="layout-error">
        <section class="error">
            <h2 class="section-title">404</h2>
            <ArticleBody>
                <h3>名前はまだない</h3>
                <p>アクセスされたページは存在しないか、すでに削除されています。</p>
            </ArticleBody>
        </section>
    </div>
</template>

<script>
import ArticleBody from '~/components/common/ArticleBody'
export default {
    components: {
        ArticleBody
    }
}
</script>

<style lang="scss" scoped>

</style>