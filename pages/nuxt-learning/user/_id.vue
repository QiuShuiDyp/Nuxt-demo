<template>
  <div>
    <p>
      <nuxt-link to="/home">返回home</nuxt-link>
    </p>
    <p>用户id是:{{ id }}</p>
    <p>动态参数路由</p>
  </div>
</template>

<script>
export default {
  validate({ params }) {
    this.id = params.id
    return true
  },
  data: () => {
    return {
      id: null,
    }
  },
}
</script>

<style lang="less"></style>
