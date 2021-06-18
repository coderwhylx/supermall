<template>
  <div>
    <!-- app
    <input type="button" value="点我试试" @click="sayhai"> -->
    <top></top>
    <index></index>
  </div>
</template>

<script>
import top from './components/top.vue'
import index from './components/index.vue'


export default {
  name: 'App',
  methods: {
    sayhai(){
      alert('你好吗')
    }
  },
  components: {
    top,
    index
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
</style>
