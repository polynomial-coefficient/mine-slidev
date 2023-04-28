<template>
  <div class="catalogDiv">
    <br />
    <table class="topicTable">
      <tr class="catalogTblTr">
        <td
          class="signTd catalogTip"
          style="border-top-left-radius: 0.3em; border-top-right-radius: 0.3em"
        >
          <span class="tdSpan">1</span>
        </td>
        <td class="topic"><h2 class="topic">选题来源</h2></td>
      </tr>
      <tr class="catalogTblTr">
        <td class="signTd catalogTip"><span class="tdSpan">2</span></td>
        <td class="topic"><h2 class="topic">论文研究的目的和意义</h2></td>
      </tr>
      <tr class="catalogTblTr">
        <td class="signTd catalogTip"><span class="tdSpan">3</span></td>
        <td class="topic"><h2 class="topic">论文研究的思路和方法</h2></td>
      </tr>
      <tr class="catalogTblTr">
        <td class="signTd catalogTip"><span class="tdSpan">4</span></td>
        <td class="topic"><h2 class="topic">论文获得的成果或结论</h2></td>
      </tr>
      <tr class="catalogTblTr">
        <td
          class="signTd catalogTip"
          style="
            border-bottom-left-radius: 0.3em;
            border-bottom-right-radius: 0.3em;
          "
        >
          <span class="tdSpan">5</span>
        </td>
        <td class="topic"><h2 class="topic">不足与展望</h2></td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  name: "catalog",
  // 组件的逻辑和数据定义
  setup() {
    // 组件的逻辑和数据逻辑
  },
};
</script>
<style scoped>
html,
body {
  height: 100%;
}
.topic {
  margin-top: 0em;
  margin-bottom: 0em;
  margin-left: 1em;
  font-size: 1.2rem;
  font-weight: bolder;
}
nav.toc {
  display: none;
}
.topicTable tr {
  border-bottom-width: 0px;
}
.catalogDiv {
  overflow: hidden;
  height: 40em;
}
table.topicTable {
  border-collapse: collapse;
  border: none;
  height: 55%;
  transform: translateX(28%);
}

td.signTd,
td.topic,
th {
  border: none;
}
.signTd {
  width: 4em;
  background-color: #164b79;
  /* border-radius: 0%; */
}

.catalogTip {
  color: white;
  text-align: center;
  font-size: 2rem;
  font-weight: lighter;
}

span.tdSpan {
  padding-bottom: 5px;
  border-bottom: 2px solid #fff;
}
</style>
