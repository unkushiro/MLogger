# MLogger
一个浮在页面上的日志查看工具

# 功能简介
一个浮在页面上的console面板，资源保证按需加载最大化保证性能。
1 查看移动web页面上的console信息，自己可以在代码里面任意使用console，然后在手机端呼起该log便可以查看自己所打印的信息。
2 查看移动web页面的ajax请求信息，包括返回数据，请求参数等等，类似与fiddler的抓包。

# 功能清单
项目分为3个资源文件
1 inline的js 这个js需要在页面的所有js之前引入(因为会拦截console方法和ajax方法).
2 非inline的js 这个js可以放在cdn上面，在初始化的时候配置进去即可。
3 非inline的css 这个css可以放在cdn上面，在初始化的时候配置进去即可。