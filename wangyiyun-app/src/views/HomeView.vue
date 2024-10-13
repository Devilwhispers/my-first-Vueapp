<template>
  <div class="home">
    <TopNav />
    <SwpierTop/>
    <IconLIst/>
    <MusicList/>
  </div>
</template>

<script>
// @ is an alias to /src
import TopNav from "@/components/home/TopNav.vue";
import SwpierTop from "@/components/home/SwpierTop.vue";
import IconLIst from "@/components/home/IconLIst.vue";
import MusicList from "@/components/home/MusicList.vue";
export default {
  name: 'HomeView',
  components: {
    TopNav,SwpierTop,IconLIst,MusicList
  }
}
</script>
