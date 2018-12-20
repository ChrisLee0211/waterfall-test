# waterfall-test
一个瀑布流组件留存仓库

## 瀑布流布局个人DEMO
- 主要用 _jQuery_ 来计算每一列高度，然后通过```position```的```left```逐列插入形成瀑布流。
- 追加下拉加载：
    1. 先判断是否拉到底部（通过滚动高度+窗体高度是否大于高度最长列来判断）；
    2. 编写一个追加函数，用 _jQuery_ 的```append```方法，在```body```的尾部新增一个```div```，样式直接套用前面的样式，然后在追加函数末尾再次调用瀑布流布局函数，完成追加。
    
    
## 实现效果预览：
![img](https://github.com/ChrisLee0211/waterfall-test/blob/master/example01.gif)
