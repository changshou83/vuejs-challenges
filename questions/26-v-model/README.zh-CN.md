<!--info-header-start--><h1>实现简易版`v-model`指令 <img src="https://img.shields.io/badge/-%E5%9B%B0%E9%9A%BE-de3d37" alt="困难"/> <img src="https://img.shields.io/badge/-%23Directives-999" alt="#Directives"/></h1><blockquote><p>By webfansplz <a href="https://github.com/webfansplz" target="_blank">@webfansplz</a></p></blockquote><p><a href="https://sfc.vuejs.org/#eNpNT7tuwzAM/BVCS1oDjvfCLlB0aYeiWyYtqk0nKiRKkCingeF/LxUvWQiQ9+Ddqt5iPC4F1Yvq85hsZMjIJYIzdB4OnA+vmjRZH0NiWCHhDBvMKXjQSnRaVbhrGk3QwKePDj0Sg4GxZBbWZBOObBe8E94TGkZB+Rraq7nBj6XJ0hkCyXEOyYOlWBhw96kiTU2naQyUGU7fl68woYMB1vp4q2OHFuMKyl0SPmn1gc4FOBU8/matniut7/aC90I9o2SVLLIB9PvTpQ2X1lf/QcpVP62AbxFlZfxj2Trh992DWG3/u8pxLg==" target="_blank"><img src="https://img.shields.io/badge/-%E6%8E%A5%E5%8F%97%E6%8C%91%E6%88%98-213547?logo=vue.js&logoColor=42b883" alt="接受挑战"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.md" target="_blank"><img src="https://img.shields.io/badge/-English-gray" alt="English"/></a> </p><!--info-header-end-->


在这个挑战中，我们将尝试实现一个简单的`v-model`指令，让我们开始吧 👇: 

```vue
<script setup lang='ts'>

import { ref } from "vue"

/**
 * 实现以下自定义指令
 * 在表单输入元素和数据间创建双向绑定
 *
*/
const VOhModel = {

}

const value = ref("Hello Vue.js")

</script>

<template>
  <input v-oh-model="value" type="text" />
</template>

```
<!--info-footer-start--><br><a href="../../README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E8%BF%94%E5%9B%9E%E9%A6%96%E9%A1%B5-grey" alt="返回首页"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues/new?labels=answer,zh-CN&template=1-answer.zh-CN.md&title=26%20-%20%E5%AE%9E%E7%8E%B0%E7%AE%80%E6%98%93%E7%89%88%60v-model%60%E6%8C%87%E4%BB%A4" target="_blank"><img src="https://img.shields.io/badge/-%E5%88%86%E4%BA%AB%E4%BD%A0%E7%9A%84%E8%A7%A3%E7%AD%94-teal" alt="分享你的解答"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues?q=label%3A26+label%3Aanswer" target="_blank"><img src="https://img.shields.io/badge/-%E6%9F%A5%E7%9C%8B%E8%A7%A3%E7%AD%94-de5a77?logo=awesome-lists&logoColor=white" alt="查看解答"/></a> <!--info-footer-end-->
