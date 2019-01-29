<template>
  <swiper :options="swiperOption">
    <swiper-slide>
        <img class="swiper-image" src="http://mp-piao-admincp.qunarzz.com/mp_piao_admin_mp_piao_admin/admin/20191/6bdcd1e29c06886d56ed847cd3f75ef6.jpg_750x200_9387edb7.jpg"/>
    </swiper-slide>
    <swiper-slide>
        <img class="swiper-image" src="http://img1.qunarzz.com/piao/fusion/1808/70/5603e6a535062402.jpg_750x200_2c552f2c.jpg" />
    </swiper-slide>
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {}
    }
  }
}
</script>

<style lang="stylus" scoped>
  .swiper-image
    width: 100%
</style>
