<!--info-header-start--><h1>切换焦点指令 <img src="https://img.shields.io/badge/-%E4%B8%AD%E7%AD%89-d9901a" alt="中等"/> <img src="https://img.shields.io/badge/-%23Directives-999" alt="#Directives"/></h1><blockquote><p>By webfansplz <a href="https://github.com/webfansplz" target="_blank">@webfansplz</a></p></blockquote><p><a href="https://sfc.vuejs.org/#eNpNUDFOxDAQ/MriJrkILhElSk6iQbqClspNyG1yFo5t2esAivJ31g7SXWNpdmfGM7uKV+eOS0TxItoweOUIAlJ0oHszdQWF4iSNmp31BCt4HGGD0dsZpGCVFNJIM1gTWEY9IXSJU469DnhIu7qqpIEKzrPTOKMhoCvCEAOxx0V5HEgtmCnv/RdCiB4zRRkXCfBfNFqWYKg/dfQBvq9oMqnInxagApCdJo2X5CRNVd9yfbwlLQdb02xLDzc8G0K/9LosD9Cd0g72BkcextTj4Q6y7hGem6bJndp6vxRfhgEhV2MmI4B2j7085cCdFNlECqBfhwwJf0gKprb1nU5sf6sriZM=" target="_blank"><img src="https://img.shields.io/badge/-%E6%8E%A5%E5%8F%97%E6%8C%91%E6%88%98-213547?logo=vue.js&logoColor=42b883" alt="接受挑战"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.md" target="_blank"><img src="https://img.shields.io/badge/-English-gray" alt="English"/></a> </p><!--info-header-end-->


这个挑战开始，我们将尝试编写自定义指令，让我们从`v-focus`开始 👇:

```vue
<script setup lang='ts'>
import { ref } from "vue"

const state = ref(false)

/**
 * 实现一个自定义指令,让元素获取焦点
 * 确保当切换`state`时,元素随着状态值获取/失去焦点
 *
*/
const VFocus = {

}

setInterval(() => {
  state.value = !state.value
}, 2000)

</script>

<template>
  <input v-focus="state" type="text">
</template>

```

<!--info-footer-start--><br><a href="../../README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E8%BF%94%E5%9B%9E%E9%A6%96%E9%A1%B5-grey" alt="返回首页"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues/new?labels=answer,zh-CN&template=1-answer.zh-CN.md&title=19%20-%20%E5%88%87%E6%8D%A2%E7%84%A6%E7%82%B9%E6%8C%87%E4%BB%A4" target="_blank"><img src="https://img.shields.io/badge/-%E5%88%86%E4%BA%AB%E4%BD%A0%E7%9A%84%E8%A7%A3%E7%AD%94-teal" alt="分享你的解答"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues?q=label%3A19+label%3Aanswer" target="_blank"><img src="https://img.shields.io/badge/-%E6%9F%A5%E7%9C%8B%E8%A7%A3%E7%AD%94-de5a77?logo=awesome-lists&logoColor=white" alt="查看解答"/></a> <!--info-footer-end-->
