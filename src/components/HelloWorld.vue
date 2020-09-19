<template>
  <div style="white-space: nowrap;">
    <div class="tab" v-for="(item,index) in tableData" :key="index">{{item}}</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      input:"",
      tableData:new Array(10).fill("12")
    }
  }
}
</script>
<style>
  .tab{
    display: inline-block;
    width:50px;
    overflow: auto;
  }
</style>