### 修复[vue-scroller](https://github.com/wangdahoo/vue-scroller)的几处bug

***
*   不加:on-refresh="refresh" 只加:on-infinite="infinite" loading的图标会不见
*   onInfinite第一次加载数据没有超出屏幕的话，loading提示一直显示
*   on-infinite刚进入会默认触发
***