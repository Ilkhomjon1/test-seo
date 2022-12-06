<template lang="html">
  <div class="container">

    <div class="line"></div>
    <!-- <el-menu
      :default-active="activeIndex2"
      class="el-menu-demo"
      mode="horizontal"
      @select="handleSelect"
      background-color="#545c64"
      text-color="#fff"
      active-text-color="#ffd04b"
    >
      <el-menu-item index="1" @click="$router.push('/')">Home</el-menu-item>
      <el-menu-item index="2" @click="$router.push('/about')">About</el-menu-item>
      <el-menu-item index="3" @click="$router.push('/seo')">Seo</el-menu-item>
      <el-menu-item index="4" @click="$router.push('/info')">Info</el-menu-item>
    </el-menu> -->
    <Nuxt />
  </div>
</template>
<script>
export default {
  data() {
    return {
      activeIndex: "1",
      activeIndex2: "1",
    };
  },
  methods: {
    handleSelect(key, keyPath) {
     
    },
  },
};
</script>
<style lang="css"></style>
