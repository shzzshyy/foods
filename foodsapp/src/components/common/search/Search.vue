<template>
  <div class="search-view">
     <img src="~@/assets/img/search.png">
      <input 
      type="text" 
      class="input-text" 
      v-model="value"
      placeholder="南京好吃的鸭子在哪里?">
  </div>
</template>

<script>
export default {
  name: 'Search',
  data () {
    return {
      value: ''
    }
  },
  props: {
    bgcColor: String
  }
}
</script>

<style>

.search-view {
  background-color: #1a1a1a;
  height: 30px;
  text-align: center;
}

.search-view .img {
  width: 18px;
  height: 18px;
  padding-top: 5px;
}

.input-text {
  text-align: center;
  outline: none;
  border-width: 0px;
  padding-top: -15px;
  height: 100%;
  background-color: rgba(1, 1, 1, 0);
  /* background-color:  red; */
  font-size: 13px;
  color: white;
}

</style>