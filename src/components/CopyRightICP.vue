<template>
  <div class="icp">{{`© ${year} ${author} `}}<a href="https://beian.miit.gov.cn" target="_blank">{{ record }}</a></div>
</template>

<script setup>
let year = new Date().getFullYear();
let author = 'BsKPLu';
let record = '苏ICP备2022020445号-1';
</script>

<style>
.icp {
  position: absolute;
  bottom: 0;
  padding: 10px 0;
  width: 100%;
  text-align: center;
  color: gray;
}
.icp > a {
  color: gray;
  text-decoration: none;
}
.icp > a:hover {
  color: aqua;
  text-decoration: none;
}
</style>

