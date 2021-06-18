<template>
  <div class="index">
      <div class="index nav">
          <ul>
              <li>发现音乐</li>
              <li>推荐歌单</li>
              <li>最近音乐</li>
              <li>最新MV</li>
          </ul>
      </div>
      <div class="main">
<discovery></discovery>
      </div>
  </div>
</template>

<script>
import discovery from './discovery.vue'
export default {
components: {
    discovery
}
}
</script>

<style>
.index{
    display: flex;
    height: 830px;
}
.index.nav{
        width: 200px;
        background-color: #ededed;
}
.index.nav.li{
    text-align: center;
    margin: 10px;
}
.main{
    background-color: orange;
    flex: 1;
}
</style>