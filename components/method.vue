<template>
  <div style="text-align: center">
    <h1>论文研究的思路与方法</h1>
  </div>
  <div class="researchOfTableDiv">
    <table class="researchTbl">
      <thead>
        <tr class="headRow">
          <th class="titleHeads"></th>
          <th class="titleHeads">概括</th>
          <th class="titleHeads">解释</th>
        </tr>
      </thead>
      <tbody>
        <tr class="researchTr">
          <td class="researchOfTd leftKeyName">研究方法</td>
          <td class="researchOfTd imgSvgTd">
            <img src="../assets/3.drawio.svg" />
          </td>
          <td class="researchOfTd">
            <p>本论文采用了文献调研法、实验法和分析法等方法</p>
            <ol>
              <li>文献调研法用于分析Unity引擎的特点、优缺点等</li>
              <li>
                实验法用于设计开发《约翰的幽灵迷宫之旅》单机游戏，并对其进行测试和优化
              </li>
              <li>
                分析法用于对游戏中使用的组件(如摄像机、动画状态机、物理引擎、刚体系统、碰撞检测等)进行分析
              </li>
            </ol>
          </td>
        </tr>
        <tr class="researchTr">
          <td class="researchOfTd leftKeyName">研究思路</td>
          <td class="researchOfTd imgSvgTd">
            <img src="../assets/2.drawio.svg" />
          </td>
          <td class="researchOfTd" style="font-size: 1rem">
            本论文以“基于Unity引擎的单机游戏设计与开发”为课题，通过对Unity引擎的特点、优缺点、组件等进行分析，设计并开发了一款名为《约翰的幽灵迷宫之旅》的单机游戏，并进行了功能测试和性能优化
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>
<script>
export default {
  name: "method",
  // 组件的逻辑和数据定义
  setup() {
    // 组件的逻辑和数据逻辑
  },
};
</script>
<style scoped>
.researchTbl {
  border-collapse: collapse;
  border-radius: 10px;
  border: 1px solid black;
}

.researchTbl th,
.researchTbl td {
  border: 2px solid #fff;
  padding: 5px;
}

.headRow th {
  text-align: center;
}

.leftKeyName {
  width: 1em;
  background-color: #ddd;
}

.imgSvgTd {
  width: 16%;
}

.titleHeads {
  background-color: #ddd;
}

h1 {
  padding-bottom: 5px;
  border-bottom: 2px solid #164a77;
}
</style>
