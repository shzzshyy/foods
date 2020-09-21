<template>
  <div class="home-search">
    <img src="~@/assets/img/toptitle.jpg" alt="">
    <Search class="search-view"></Search>
  </div>
</template>

<script>
import { Toast } from 'vant';
import Search from '@/components/common/search/Search'

export default {
  name: 'HomeSearch',
  data() {
    return {
      searchValue: '',
    }
  },
  components: {
    Search
  },
  methods: {
    onSearch(val) {
      Toast(val);
    },
    onCancel(val) {
      Toast(val);
    },
    btnClick() {
      alert(this.searchValue)
    }
  }
}
</script>

<style scoped>
.home-search {
  background-color: #eff1f2;
}

.home-search img {
  width: 100%;
}

.search-view {
  margin: 0 15px;
  border-radius: 6px;
}

</style>