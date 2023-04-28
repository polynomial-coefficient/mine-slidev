<template>
  <div class="container">
    <div class="titleDiv">
      <h1 class="title">基于灵族方舟引擎的阿玛达6型舰船建造</h1>
    </div>
    <div class="contentDiv">
      <table class="myTable">
        <tr>
          <td class="mineKey">姓名</td>
          <td class="mineVal">伊巴实</td>
        </tr>
        <tr>
          <td class="mineKey">指导教师</td>
          <td class="mineVal">阿米诺斯</td>
        </tr>
        <tr>
          <td class="mineKey">班级专业</td>
          <td class="mineVal">1919810级114514班</td>
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
  // 组件的逻辑和数据定义
  setup() {
    // 组件的逻辑和数据逻辑
  },
};
</script>

<style scoped>
.title {
  font-size: 2rem;
  /* margin-bottom: 1rem; */
}

.title {
  text-align: center; /* 标题居中对齐 */
}

.contentDiv {
  position: relative; /* 设置为相对定位 */
  left: 0%; /* 将 div 元素向右移动 50px */
}

.titleDiv {
  transform: translateY(-90%);
}

.mineKey {
  text-align: right;
  word-wrap: break-word;
  width: 43%;
}

.mineVal {
  text-align: left;
}

.myTable {
  border: none;
  border-collapse: collapse;
  font-size: 1.4em; /* 控制表格中所有文字的大小 */
}

.myTable td {
  border: none;
  color: #020000; /* 控制表格中所有单元格的文字颜色 */
}

.myTable tr {
  border-bottom-width: 0px;
}
</style>
