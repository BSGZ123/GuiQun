# YanCheng GuiJun engineering management 基于Shanghai kejian engineering management前端项目 感谢原作者feng的无私开源
> 桂君智能化工程有限公司企业官网 前端    


## 已完成的改进
1. 已经更新到vue2新的依赖版本，解决了部分安全问题。
2. 已经与原作者提供的KeJian.Core.Api后端对接

## 计划中的改进
1. 修复优化页面显示
2. 后续在原基础上重构为vue3

推荐部署环境Nodejs 16.20.0或12.22.12版本 以上版本都是本人部署成功的
后端的代码 这里 https://github.com/BSGZ123/KeJian.Core.Api

## 新版本改进（原作者记录）
1. 整体重构，结构升级为最新 vue-cli3
2. 代码优化，去除引用的静态js文件
3. 图片加载加入懒加载，整体性能提升很大
4. 视频采用 vue-video-player 处理兼容性
5. 首页全屏滚动样式由静态文件 fullpage.js 改为 vue-awesome-swiper
6. 样式调整，提升了自适应能力

## 组件列表
1. vue-router
2. element-ui
3. axios
4. vue-video-player (视频组件)
5. vue-awesome-swiper (首页滚动组件)
6. vue-lazyload (图片懒加载)

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```
