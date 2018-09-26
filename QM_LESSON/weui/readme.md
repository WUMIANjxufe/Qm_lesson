- css命名规范BEM
Block
页面是由多个Block构成的，跟其它的block区分开来，tabbar
Element__
在区块中担负的职责，取唯一性的名字
并不是简单地父子关系
_label
_icon
MOdifier
状态的修改
__item_
on
- WEUI
微信UI规范，内嵌公众号，小程序，调起webview,为了让用户体验一致，让用户有认同感。
mobile web app
前端界面框架weui.css
- 组件
大部分的项目，70%都是通用组件构成的，组件，拿来就用。
1. tabbar
.tabbar>a.item>(span>img+span.badge)+p
词汇量 组件词汇量tabbar badge 一般词汇
item
良好的结构和语义化标签
flex 1:1:1
http状态码
有状态码，方便分析
2开头的 都是好 200
3开头 跳转
4开头 404 not found 403无权使用
5开头 错误
