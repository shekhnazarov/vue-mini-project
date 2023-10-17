<template>
  <div class="app">
    <div class="content">
      <AppInfo />
      <AppFilter />
    </div>
  </div>
</template>
<script>
import AppFilter from './AppFilter.vue'
import AppInfo from './AppInfo.vue'

export default { components: { AppInfo, AppFilter } }
</script>
<style>
.app {
  height: 100vh;
  color: #000;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: blanchedalmond;
}

.content {
  width: 1000px;
  min-height: 700px;
  background-color: #fff;
}
</style>
