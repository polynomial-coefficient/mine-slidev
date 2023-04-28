<template>
  <div class="firstTitle">
    <h1>选题来源</h1>
  </div>
  <br />
  <div class="tblDiv">
    <table class="OwnTable">
      <tr>
        <td class="leftColumnTd">宏观因素1</td>
        <td class="rightColumnTd">电子游戏的流行</td>
      </tr>
      <tr>
        <td class="leftColumnTd">宏观因素2</td>
        <td class="rightColumnTd">Unity引擎知名度高</td>
      </tr>
      <tr>
        <td class="leftColumnTd">个人因素</td>
        <td class="rightColumnTd">对游戏开发充满好奇</td>
      </tr>
      <tr>
        <td class="leftColumnTd">结果</td>
        <td class="rightColumnTd">敲定课题</td>
      </tr>
    </table>
  </div>
</template>
<script>
export default {
  name: "selecting",
  // 组件的逻辑和数据定义
  setup() {
    // 组件的逻辑和数据逻辑
  },
};
</script>
<style scoped>
table {
  border: 0;
  border-collapse: collapse;
}

td {
  border: 0;
}

.OwnTable {
  font-size: 1.5rem;
  transform: translateX(27%);
  font-weight: lighter;
}

.OwnTable tr {
  border-bottom-width: 0px;
  height: 3em;
}
.firstTitle > h1 {
  text-align: center;
  padding-bottom: 5px;
  border-bottom: 2px solid #164a77;
}
.leftColumnTd {
  text-align: right;
  width: 6em;
}
</style>
