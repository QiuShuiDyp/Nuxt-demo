<template>
  <div>
    <p>
      <nuxt-link to="/home">返回home</nuxt-link>
    </p>
    <p>这是用户页面</p>
  </div>
</template>

<script>
export default {
  name: 'UserInfo',
  layout: 'default',
  data() {
    return {
      userName: '',
    }
  },
}
</script>

<style lang="less"></style>
