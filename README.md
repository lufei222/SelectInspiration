# sanVariousProject
##本项目顾名思义：多个业务或场景的项目集合
-我的多个业务或场景的测试
-对于不同的业务场景
-都是建立在不同的目录下面进行的
-所以每个目录下面都有一个readme.md说明
#selectUsePlugins
**是为了测试元素操作html自带的select的节点展开与收缩而进行的一系列测试页面**
**最后发现在移动端均无法实现对原声select的操作**
#customselect
**是为了解决无法通过其他节点操作原声select的节点展开而重写的模拟select下拉框的一些页面**
**目的是替换select。完成普通标签操作下拉框展开和收缩**

#要在手机端运行项目，则需要另起nodejs服务器环境
启动步骤：
1：安装nodejs
2：把http.js和mine.js放在sanVariousProject的上一级目录
3：修改http.js里面的  var realPath = path.join("sanVariousProject", pathname);//这里填写当前项目对应的项目名称，并且这个js和mine,js都要放在本项目的上一级目录，作为nodejs服务器脚本
