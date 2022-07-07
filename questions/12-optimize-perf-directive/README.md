<!--info-header-start--><h1>Optimize performance directive <img src="https://img.shields.io/badge/-medium-d9901a" alt="medium"/> <img src="https://img.shields.io/badge/-%23Directives-999" alt="#Directives"/> <img src="https://img.shields.io/badge/-%23Built--ins-999" alt="#Built-ins"/></h1><blockquote><p>By webfansplz <a href="https://github.com/webfansplz" target="_blank">@webfansplz</a></p></blockquote><p><a href="https://sfc.vuejs.org/#eNpNjTEOgzAQBL+ycgUiIqRFgJQyRX7gxkJHggKHZc40lv8eW6RIuavZnaDu1taHJ9Wqbh/dbAU7ibeD5nm1mxMEOJoQMblthVaJ1Uqz5nHjXTBungV9ZoqmzH2aP1jIHWYpihL9gKAZJ1in0lNVaY4X3JomL7rr6U3GFIRWuxihlIBut4aHp/kQZgHTQQ7j2/CLWoTwc8eYHjKXr/7mKn4BPe9M6A==" target="_blank"><img src="https://img.shields.io/badge/-Take%20the%20Challenge-213547?logo=vue.js&logoColor=42b883" alt="Take the Challenge"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-gray" alt="简体中文"/></a> </p><!--info-header-end-->


`Vue.js` provides a directive that renders the element and the component only once, and skips future updates.

Do you know what the directive is?. Lets try it 👇: 

```vue
<script setup>
import { ref } from "vue"

const count = ref(0)

setInterval(() => {
  count.value++
}, 1000)
</script>

<template>
  <span>Make it not to change: {{ count }}</span>
</template>

```

<!--info-footer-start--><br><a href="../../README.md" target="_blank"><img src="https://img.shields.io/badge/-Back-grey" alt="Back"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues/new?labels=answer,en&template=0-answer.md&title=12%20-%20Optimize%20performance%20directive" target="_blank"><img src="https://img.shields.io/badge/-Share%20your%20Solutions-teal" alt="Share your Solutions"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues?q=label%3A12+label%3Aanswer" target="_blank"><img src="https://img.shields.io/badge/-Check%20out%20Solutions-de5a77?logo=awesome-lists&logoColor=white" alt="Check out Solutions"/></a> <!--info-footer-end-->
