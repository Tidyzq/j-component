# 更新日志

## 1.1.7

* 废弃注册组件时对初始 data 进行深拷贝的逻辑。
* 修复组件 dispatchEvent 方法中自定义事件传入 detail，组件函数接收不到 detail 的问题（#7）。