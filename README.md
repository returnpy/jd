# 京东 PC端口

## 网站制作流程
1. 客户沟通制定方案
2. 签订合同
3. 预付定金
4. 初稿审核
5. 前台页面设计 后台功能开发
6. 测试验收
7. 线上培训
8. 后期维护


产品原型图
效果图


## 项目规划
整体介绍
  一个电商网站，我们需要完成 PC 端首页、列表页、注册页
学习目的
  电商类网站比较综合，里面需要大量的布局，包括布局方式，常见效果以及周边技术
  复习总结提高布局技术
  对实际制作 PC 端页面流程有一个整体感知
  为移动端项目做铺垫
开发工具和技术栈
  VScode  Chrome
  HTML5 + CSS3 可以大量使用新标签，新样式
  采用结构与样式分离，模块化开发
  良好的代码规范有助于团队开发协作，提高代码质量


## 模块化开发
  将项目按功能拆分成模块，模块与模块之间互不影响
  模块化开发具有代码重用，更换方便等优点

## 网站 TDK 三大 SEO 标签
title
meta
  description
  keywords

## 常见模块命名
快捷导航栏    shortcut
头部         header
logo
shopcar
search
hotwords
nav
dropdown .dd .dt
navitems
footer
mod_service
mod_help
mod_copyright


## logo SEO 优化
logo 里面放一个 h1 标签，告诉搜索引擎，这个地方很重要
h1 里面再放一个链接，可以返回首页，把 logo 的背景图片给链接即可
为了搜索引擎更好的收录，链接里面要放文字（网站名称）但是文字不要显示出来
    text-indent: -999px;
    font-size: 0;
给链接添加 title 属性