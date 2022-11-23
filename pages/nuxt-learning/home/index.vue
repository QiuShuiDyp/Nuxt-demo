<template>
  <div class="main">
    <p>{{ text }}</p>
    <img src="/favicon.ico" alt="" />
    <p><nuxt-link to="/user/123">id为123的页面</nuxt-link></p>
    <img src="~/assets/home/china.jpg" alt="" />
    <p><nuxt-link to="/user">我的页面</nuxt-link></p>
    <p><nuxt-link to="/article/list">博客页</nuxt-link></p>
    <p><nuxt-link to="/article/ArticleList">博客列表</nuxt-link></p>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  layout: 'TechnicalColumn',
  asyncData(ctx) {
    console.log(ctx, 'ctx')
    return { text: 'Hello,这是首页' }
  },
  data: () => {
    return {}
  },
}
</script>

<style>
.main {
  padding: 20px;
}
</style>
