<template>
  <div class="paper-results" style="text-align: center">
    <h1>论文获得的成果与结论</h1>
    <br />
    <table class="paper-table">
      <thead>
        <tr>
          <th class="title-header" style="text-align: center">成果</th>
          <th class="title-header" style="text-align: center">结论</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>基于Unity引擎，开发了一款名为《约翰的幽灵迷宫之旅》的单机游戏</td>
          <td>Unity具有良好的跨平台性和易用性</td>
        </tr>
        <tr>
          <td>
            深入了解Unity引擎中许多组件的应用，掌握游戏开发的流程和技术细节
          </td>
          <td>
            游戏设计与开发是一个综合性的过程，需要深入理解游戏开发的流程和技术细节
          </td>
        </tr>
        <tr>
          <td>在开发游戏方面积累了实践经验</td>
          <td>游戏开发需要注重细节，比如场景设计、玩法设置、素材管理等方面</td>
        </tr>
        <tr>
          <td></td>
          <td>不断测试和优化能得到更优秀的游戏作品</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>
<script>
export default {
  name: "result",
  // 组件的逻辑和数据定义
  setup() {
    // 组件的逻辑和数据逻辑
  },
};
</script>
<style scoped>
.paper-results {
  margin: 20px;
}

.paper-table {
  border-collapse: collapse;
  width: 100%;
}

.paper-table th,
.paper-table td {
  padding: 10px;
  text-align: left;
  border: 1px solid black;
}

.paper-table th {
  background-color: #ddd;
}

.paper-table td {
  background-color: #fff;
  text-align: center;
}

h1 {
  padding-bottom: 5px;
  border-bottom: 2px solid #164a77;
}
</style>
