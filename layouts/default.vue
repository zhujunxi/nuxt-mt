<template>
  <el-container>
    <el-header>
      <MyHeader></MyHeader>
    </el-header>
    <el-main>
      <nuxt></nuxt>
    </el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>
<script>
import MyHeader from '@/components/public/header/index.vue'

export default {
  components: {
    MyHeader
  }
}
</script>
