<template>
    <div class="page-about">
        <section class="about">
            <h2 class="section-title">はじめました</h2>
            <ArticleBody>
                <p>たけうま。2010年にプログラマとしてシステム開発に従事</p>
                <p>2018年にITコンサルに職種を変え、システム開発におけるPMO業務に従事</p>
            </ArticleBody>
        </section>

        <section class="history">
            <h2 class="section-title">経歴</h2>
            <ArticleBody>
                <h3>2010～2016年</h3>
                <p>ストレージ管理ソフトウェア開発</p>
                <h3>2017~2018年</h3>
                <p>空港系システム開発</p>
                <h3>2018/2～2019/7</h3>
                <p>インフラ</p>
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

<style scoped lang="scss">
</style>