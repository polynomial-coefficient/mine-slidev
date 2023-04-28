<template>
  <div>
    <div class="titleDiv">
      <h1 class="title-h1">论文研究的目的和意义</h1>
    </div>
    <div class="mineTableDiv">
      <table class="mine-table">
        <tr class="mine-tr">
          <td class="left-column commonColumn">意义</td>
          <td class="right-column commonColumn">
            通过实践深入学习Unity引擎和相关工具, 提升个人技能水平
          </td>
        </tr>
      </table>
    </div>
    <div class="pictureDiv">
      <img src="../assets/sample00.gif" alt="游戏截图" class="gifTag2" />
    </div>
  </div>
</template>
<script>
export default {
  name: "purpose2",
  // 组件的逻辑和数据定义
  setup() {
    // 组件的逻辑和数据逻辑
  },
};
</script>
<style scoped>
.mine-table {
  border-collapse: collapse;
  border: none;
  transform: translateX(11%);
}

.title-h1 {
  text-align: center;
  padding-bottom: 5px;
  border-bottom: 2px solid #164a77;
}

.left-column {
  text-align: right;
}

.mine-tr {
  border-bottom-width: 0px;
  height: 0em;
  font-size: 1.3rem;
  font-weight: lighter;
}

.commonColumn {
  font-size: 1em;
}

.gifTag2 {
  width: 100rem;
  height: 21rem;
  border-radius: 10px;
}
</style>
