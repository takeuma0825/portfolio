<template>
  <div class="page-index">
    <section class="about">
      <h2>たけうま</h2>
      <ArticleBody>
        <img src="~/assets/images/takeuma.jpg" alt="たけうま">
        <p>エンジニア兼、ITコンサル</p>
      </ArticleBody>
    </section>

    <section class="works">
      <h2>ITスキル</h2>
      <ArticleBody>
        <p>Programming language.</p>
        <ul>
          <li>Java</li>
          <li>SQL</li>
          <li>C/C++</li>
          <li>python</li>
          <li>vue, nuxt</li>
        </ul>
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

.about,
.works {
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
</style>
