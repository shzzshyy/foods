<template>
  <div class="home-center">
    <div class="top">
      <div class="left-item">火爆餐厅</div>  
      <div class="right-item">
        MORE <img src="~@/assets/img/arrow-right.png">
      </div>
    </div>  
    <div class="center">
      <div class="center-left">
        <img src="~@/assets/img/image-left.jpg" class="image-left"/>
      </div>
      <div class="center-right">
        <img src="~@/assets/img/image-right-top.jpg">
        <img src="~@/assets/img/image-right-bottom.jpg">
      </div>
      
      <div class="center-bottom"></div>
    </div>
    <div class="bottom"></div>
  </div>
</template>

<script>
export default {
  name: 'HomeCenter'
}
</script>

<style scoped>

.home-center {
 background-color: #eff1f2;
}

.top {
  font-weight: 700;
  margin: 22px 15px;
  display: flex;
  justify-content: space-between;
}

.left-item {
  font-size: 16px;
}

.right-item {
  font-size: 14px;
}

.center {
   background-color: #eff1f2;
   display: flex;
   /* justify-content: space-between; */
}

.center-left {
 margin: 0 15px;
}


.image-left {
  height: 150px;
}
.center-right {
  background-color: salmon;
  /* flex-direction: column; */
}

.center-right img {
  height: 60px;
}
</style>>

