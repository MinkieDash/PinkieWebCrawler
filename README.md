# PinkieWebCrawler
大家好，这里明琪黛西，既是一个写手，也算是一个极客迷，我既喜欢文学，又热爱信息技术方面的知识，所以我很高兴能够在这里发布我的第一个程序作品，这个就是萍琪网页爬虫，这个作品创作的主要目的是方便brony社区从别的网站搬运小马资源并放送小马资源的推荐，此程序目前已经实现了第一个测试专用的功能，从4399获取所有小马音乐的4399链接、图片、音乐名字以及介绍，由于此程序是我的第一个程序，程序代码方面可能有很多bug和不足，所以还请大家多多指教。

更新日志：

Beta-v0.5

PinkieWebCrawler-Beta-v0.5，更新fimtale搜索引擎调用模块，调用fimtale搜索模块会从fimtale站中搜索到带有指定关键词的资源，并返回一个封装有fimtale搜到的资源基本概括的字典的列表。

指令介绍

Search.FimtaleSearch(q=None,sortby=None,cat=None,page=1)

q：默认值为None，参数表示的是要检索的关键词，参数类型为string。

sortby：默认值为None，参数表示的是排序方式，类型为string，通常情况下键入default就行。

sortby可键入的参数值：

default:表示fimtale默认排序方式

publish:按发布时间排序

update:按更新时间排序

lasttime:按回复时间排序

wordcount:按字数排序

replies:按回复数量排序

view:按浏览量排序

—————以上是可键入参数值———————

cat:默认值为None，该参数表示的是搜索的类型，一般填fiction，

cat可键入的参数值:

fiction:文楼

picture:图楼

blog:帖子

—————以上是cat可键入参数值—————————————————————————————————

page，默认值为1，该参数表示检索的起始页面，一般用于特殊需求和递归使用，通常可以不用修改。



Beta-v0.4
已经初步实现了从4399小马专区爬取基本小马资源的功能。
