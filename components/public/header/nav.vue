<template>
  <div class="m-nav">
    <ul class="nav">
      <li class="list">
        <nuxt-link to="/my">我的美团</nuxt-link>
        <dl>
          <dd><nuxt-link to="/my">我的订单</nuxt-link></dd>
          <dd><nuxt-link to="/my">我的收藏</nuxt-link></dd>
          <dd><nuxt-link to="/my">抵用券</nuxt-link></dd>
          <dd><nuxt-link to="/my">账户设置</nuxt-link></dd>
        </dl>
      </li>
      <li>
        <nuxt-link to="/order">手机APP</nuxt-link>
      </li>
      <li class="list bd">
        <nuxt-link to="/center">商家中心</nuxt-link>
        <dl>
          <dd><nuxt-link to="/center">11</nuxt-link></dd>
          <dd><nuxt-link to="/center">11</nuxt-link></dd>
          <dd><nuxt-link to="/center">11</nuxt-link></dd>
          <dd><nuxt-link to="/center">11</nuxt-link></dd>
          <dd><nuxt-link to="/center">11</nuxt-link></dd>
        </dl>
      </li>
      <li class="list site">
        <nuxt-link to="/site">网站导航</nuxt-link>
        <div class="subContainer">
          <dl class="hotel">
            <dt>五星级酒店</dt>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
            <dd>如家如家</dd>
          </dl>
          <dl class="food">
            <dt>中国美食</dt>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
            <dd>美食美食</dd>
          </dl>
          <dl class="movie">
            <dt>热映电影</dt>
            <dd>电影电影</dd>
            <dd>电影电影</dd>
            <dd>电影电影</dd>
            <dd>电影电影</dd>
            <dd>电影电影</dd>
            <dd>电影电影</dd>
          </dl>
          <dl class="app">
            <img 
              src="http://s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/appicons/meituan.png"
              alt="">
            <img
              src="http://s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/appicons/meituan.png"
              alt="">
            <img
              src="http://s0.meituan.net/bs/fe-web-meituan/e5eeaef/img/appicons/meituan.png"
              alt="">
          </dl>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  }
}
</script>

<style>
</style>
