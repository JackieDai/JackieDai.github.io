# 计算属性
参考网址

[摘自掘金](https://juejin.im/post/5d01a81d51882559ef78e498)

[官方文档](https://cn.vuejs.org/v2/guide/computed.html)

计算属性由两部分组成：get和set，分别用来获取计算属性和设置计算属性。默认只有get，如果需要set，要自己添加。另外set设置属性，并不是直接修改计算属性，而是修改它的依赖。

