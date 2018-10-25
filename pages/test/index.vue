<template>
  <section class="container">
    <img src="/pics2648.gif" usemap="#ImageMap" alt="" />
    <map name="ImageMap">
      <area shape="circle" coords="323,220,126" href="#" alt="" />
    </map>
  </section>
</template>

<script>
import $ from 'jquery'
require('image-map')
export default {
  created() {
    $('img[usemap]').imageMap()
  }
}
</script>