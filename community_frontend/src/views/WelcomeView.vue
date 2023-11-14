<script  setup>


</script>

<template>
  <div style="width: 100vw;height: 100vh;overflow: hidden;display: flex">

    <div style="flex: 1">
      <el-image style="width: 100%;height: 100%" fit="cover"
                src="https://magdeleine.co/wp-content/uploads/2023/01/52274621253_0f3ae470af_o-1400x875.jpg"></el-image>
    </div>

    <div class="welcome-title" style="font-size: 30px;font-weight: bold">
      校园论坛交流平台
    </div>

    <div class="right-card">
      <router-view />
    </div>
  </div>

</template>

<style scoped>

.welcome-title {
  position: absolute;
  bottom: 30px;
  left: 30px;
  color: white;
}

.right-card {
  width: 400px;
  z-index: 1;
  background-color: white;

}

</style>
