<template>
  <div class="box">
    <span class="bd">Hello, DSL plugin developer</span>
    <div class="ft">
      <div class="outer">
        <span class="getStart">Get start</span>
        <span class="title">How to develop your own dsl plugin?</span>
        <div class="itemWrap"><img class="item" :src="constants.image1" /></div>
        <div class="tryWrap"><span class="try">Try</span></div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      constants: {
        image1:
          'https://gw.alicdn.com/tfs/TB1QbFSqi_1gK0jSZFqXXcpaXXa-440-414.png'
      }
    };
  },
  methods: {}
};
</script>
<style src="./index.css" />
