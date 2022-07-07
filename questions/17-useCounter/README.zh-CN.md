<!--info-header-start--><h1>计数器 <img src="https://img.shields.io/badge/-%E4%B8%AD%E7%AD%89-d9901a" alt="中等"/> <img src="https://img.shields.io/badge/-%23Composable%20Function-999" alt="#Composable Function"/></h1><blockquote><p>By webfansplz <a href="https://github.com/webfansplz" target="_blank">@webfansplz</a></p></blockquote><p><a href="https://sfc.vuejs.org/#eNqFUD1PwzAQ/SunLNCoImWNkgJiYkBMMHlxzRWsOo5ln/lQ5P/O2SlRkSqxRDm/j3vvpurOuauPiFVbdUF57QgCUnRgpH3rLyhcbIUVVltCv5cK4Tng/Rjz+ORIjzbAJCzAoO1NCzYOO/Rlll8nc8oeTV0zUsPD4AwOaAnoHUGNgxuD3BmEfbQqWxbWozwghOixsH4h+Bz9IbDIe1RkvoWtG2EXNC7hLrXVpKV5kSYi9LBZwzjnbc9U6GFKq1zkGFXxI8HEe5i2Bm3VGl6RPx75OpBYcLKKvad8gDZv4eItXG8grbJR18xHLUfsCLm6JOQJoHPbYtDCdFwEKXWNm8FdJOJCt8podehFxRFEVSDIcQqnmUnnBRx3EeT/fwWl2iKZp7+irjkpUKUffqLGcw==" target="_blank"><img src="https://img.shields.io/badge/-%E6%8E%A5%E5%8F%97%E6%8C%91%E6%88%98-213547?logo=vue.js&logoColor=42b883" alt="接受挑战"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.md" target="_blank"><img src="https://img.shields.io/badge/-English-gray" alt="English"/></a> </p><!--info-header-end-->


在这个挑战中，我们将实现一个计数器。 👇: 


```vue
<script setup lang='ts'>

interface UseCounterOptions {
  min?: number
  max?: number
}

/**
 * 实现计数器函数,确保功能正常工作
 * 1. 加 (+)
 * 2. 减 (-)
 * 3. 重置 
 * 4. 最小值 & 最大值 选项支持
*/
function useCounter(initialValue = 0, options: UseCounterOptions = {}) {

}

const { count, inc, dec, reset } = useCounter(0, { min: 0, max: 10 })

</script>

```
<!--info-footer-start--><br><a href="../../README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E8%BF%94%E5%9B%9E%E9%A6%96%E9%A1%B5-grey" alt="返回首页"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues/new?labels=answer,zh-CN&template=1-answer.zh-CN.md&title=17%20-%20%E8%AE%A1%E6%95%B0%E5%99%A8" target="_blank"><img src="https://img.shields.io/badge/-%E5%88%86%E4%BA%AB%E4%BD%A0%E7%9A%84%E8%A7%A3%E7%AD%94-teal" alt="分享你的解答"/></a> <a href="https://github.com/webfansplz/vuejs-challenges/issues?q=label%3A17+label%3Aanswer" target="_blank"><img src="https://img.shields.io/badge/-%E6%9F%A5%E7%9C%8B%E8%A7%A3%E7%AD%94-de5a77?logo=awesome-lists&logoColor=white" alt="查看解答"/></a> <!--info-footer-end-->
