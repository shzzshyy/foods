<template>
	<div class="home">
    <NavBar>
      <div slot="left">
        <van-icon name="location-o" />
        <span>佛山</span>
      </div>
      <div slot="center">
        吃饭吃饭
      </div>
    </NavBar>
    <HomeSearch></HomeSearch>
    <Homecenter></Homecenter>
	</div>
</template>

<script>
import NavBar from '@/components/common/navbar/NavBar'
import HomeSearch from './childComponent/HomeSearch'
import Homecenter from './childComponent/HomeCenter'

	export default {
    name:'home',
    components: {
      NavBar,
      HomeSearch,
      Homecenter
    }
	}
</script>

<style scoped>

.home {
  background-color: #eff1f2;
}

</style>>

