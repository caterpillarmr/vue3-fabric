<template>
  <div class="container">
    <div style="width: 100%; margin-bottom: 30px; border: 1px solid #f6f6f6">
      <div class="title">航空院校招生</div>
      <div class="category">
        <div class="category-title">招生专业：</div>
        <div class="category-box">
          <span class="active">空姐/空少</span>
          <span>飞行员</span>
          <span>高铁乘务</span>
          <span>地铁勤务</span>
          <span>酒店管理</span>
          <span>游轮海承</span>
        </div>
      </div>
      
      <div class="category">
        <div class="category-title">学校地区：</div>
        <div class="category-box">
          <span class="active">北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>
          <span>北京</span>   
        </div>
      </div>
      
      <div class="category">
        <div class="category-title">学习时间：</div>
        <div class="category-box">
          <span class="active">短期培训</span>
          <span>1-2年</span>
          <span>3-4年</span>
        </div>
      </div>
      
      <div class="category">
        <div class="category-title">已选条件：</div>
        <div class="category-box">
          <span class="del">短期培训</span>
        </div>
      </div>
    </div>
  </div>
</template>
<script lang="ts" setup>
</script>
<style lang="less">
.container {
  width: 1200px;
  margin: 0 auto;
}
.title {
  font-size: 16px;
  color: #315ffc;
  background-color: #f6f6f6;
  height: 50px;
  line-height: 50px;
  padding-left: 20px;
}
.category{
  font-size: 14px;
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding-left: 20px;
  padding-right: 20px;
  padding-top: 10px;
  border-bottom: 1px solid #f6f6f6;
  .category-title{
    display: inline-block;
    padding: 5px;
  }
  .category-box{
    flex: 1;
  }
}
.category-box span{
  display: inline-block;
  margin-left: 10px;
  margin-bottom: 10px;
  padding: 5px;
  border-radius: 5px;
  border: 1px solid #f6f6f6;
  width: 80px;
  text-align: center;
  height: auto;
  cursor: pointer;
  &:hover{
    color: #fff;
    background-color: #315ffc;
  }
}
.active,.del{
  position: relative;
  color: #fff;
  background-color: #315ffc;
}
.del::after{
  content: "X";
  position: absolute;
  font-size: 10px;
  top: -5px;
  right: -20px;
  color: #fff;
  border-radius: 50%;
  background-color: #315ffc;
  text-align: center;
  width: 15px;
  height: 15px;
  line-height: 15px;
}

</style>
