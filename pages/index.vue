<template>
  <div class="main">
    <h1>个人学习demo</h1>
    <ul>
      <li>
        <nuxt-link to="/nuxt-learning/home">Nuxt</nuxt-link>
      </li>
      <li><nuxt-link to="/vue3/home">Vue3</nuxt-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
<style scoped></style>
