<template>
  <div class="page-index">
    <section class="about">
      <h2>たけうま</h2>
      <div class="article-body">
        <img src="~/assets/images/takeuma.jpg" alt="たけうま">
        <p>エンジニア兼、ITコンサル</p>
      </div>
    </section>

    <section class="works">
      <h2>ITスキル</h2>
      <div class="article-body">
        <p>Programming language.</p>
        <ul>
          <li>Java</li>
          <li>SQL</li>
          <li>C/C++</li>
          <li>python</li>
          <li>vue, nuxt</li>
        </ul>
      </div>
    </section>
  </div>
</template>

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
    list-style:circle;
    margin-top: 20px;
    margin-left: 20px;

    li {
      &:nth-of-type(n+2) {
        margin-top: 0.5em;
      }
    }
  }

  img {
    max-width: 100%;
  }
}
</style>
