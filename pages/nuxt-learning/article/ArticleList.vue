<template>
  <div>
    <!-- 文章标题 -->
    <p v-for="(item, index) in list" :key="index">
      <nuxt-link :key="index" :to="item.url">{{ item.name }}</nuxt-link>
    </p>
    <!-- 文章内容 -->
    <div>
      <!-- <nuxt-child /> -->
    </div>
  </div>
</template>

<script>
export default {
  layout: 'blog',
  data: () => {
    return {
      list: [
        {
          name: '文章1',
          url: '/article/1',
        },
        {
          name: '文章2',
          url: '/article/2',
        },
        {
          name: '文章3',
          url: '/article/3',
        },
      ],
    }
  },
}
</script>

<style lang="less"></style>
