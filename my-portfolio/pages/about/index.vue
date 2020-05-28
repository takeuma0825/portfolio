<template>
    <div class="page-about">
        <section class="about">
            <h2>はじめました</h2>
            <div class="article-body">
                <p>たけうま。2010年にプログラマとしてシステム開発に従事</p>
                <p>2018年にITコンサルに職種を変え、システム開発におけるPMO業務に従事</p>
            </div>
        </section>

        <section class="history">
            <h2>経歴</h2>
            <div class="article-body">
                <h3>2010～2016年</h3>
                <p>ストレージ管理ソフトウェア開発</p>
                <h3>2017~2018年</h3>
                <p>空港系システム開発</p>
                <h3>2018/2～2019/7</h3>
                <p>インフラ</p>
            </div>
        </section>
    </div>
</template>


<style scoped lang="scss">
@import "~assets/scss/variables";

.about,
.history {
    h2 {
        display: flex;
        align-items: center;
        margin: 50px 0 30px;
        font-size: 30px;

        &::after {
            content: '';
            display: block;
            flex: 1;
            height: 1px;
            margin-left: 10px;
            background-color: $color-black;
        }
    }
}

.article-body {
    h3 {
        font-size: 20px;
        margin: 30px 0 20px;
    }

    p {
        line-height: 1.75;

        + p {
            margin-top: 20px;
        }

        a {
            color: $color-blue;
        }
    }

    ul {
        list-style: circle;
        margin-top: 20px;
        margin-left: 20px;

        li {
            &::nth-of-type(n+2) {
                margin-top: 0.5em;
            }
        }
    }

    img {
        max-width: 100%;
    }
}

</style>