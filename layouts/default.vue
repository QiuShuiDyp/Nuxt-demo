<template>
  <!-- 应用的默认布局 -->
  <div>
    <nuxt />
    <footer class="footer">
      <p>developed by QiuShui</p>
      <p>个人学习demo</p>
    </footer>
  </div>
</template>

<script>
export default {}
</script>
<style scoped>
.footer {
  position: absolute;
  bottom: 0;
  padding: 20px;
  width: 100%;
  background: grey;
  text-align: center;
}
</style>
