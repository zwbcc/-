<template>
  <div class="m-header">
    <el-col>
      <top-bar/>
    </el-col>
    <el-col>
      <search-bar/>
    </el-col>
  </div>
</template>

<script>
import topBar from './topbar'
import searchBar from './searchbar'
export default {
  components: {
    topBar,
    searchBar
  },
  data() {
    return {}
  }
}
</script>

<style lang="scss">
@import '@/assets/css/public/layout.scss';
@import '@/assets/css/public/header/index.scss';
</style>
