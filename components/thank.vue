<template>
  <div>
    <br /><br />
    <div class="thankTitle">
      <h1 style="font-size: 3rem">致谢</h1>
    </div>
    <br /><br /><br /><br /><br />
    <div class="thankContent">
      <h2>谢谢各位的聆听</h2>
    </div>
    <br /><br /><br /><br /><br /><br />
    <div class="thankContent">
      <h2>End</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: "thank",
  // 组件的逻辑和数据定义
  setup() {
    // 组件的逻辑和数据逻辑
  },
};
</script>
<style scoped>
.thankTitle {
  text-align: center;
}

/* .thankTitle h1 {
  padding-bottom: 5px;
  border-bottom: 2px solid #164a77;
  padding-bottom: 1rem;
} */

.thankContent {
  text-align: center;
}

.thankContent h2 {
  font-size: 2.5rem;
}
</style>
