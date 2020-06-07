<template>
  <div class="page-index">
    <section class="about">
      <h2 class="section-title">たけうま</h2>
      <ArticleBody>
        <img src="~/assets/images/takeuma.jpg" alt="たけうま">
        <p>エンジニア兼、ITコンサル</p>
      </ArticleBody>
    </section>

    <section class="works">
      <h2 class="section-title">ITスキル</h2>
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
</style>
