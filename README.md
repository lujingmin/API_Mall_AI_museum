# 博物馆动静皆宜
************
## PRD价值主张设计
### PRD加值宣言（使用场景）
* 每一件展品都不应该“默默无闻”
* 目标用户：来博物馆的游客
## 用户痛点：
（1） 博物馆人手不足，无法为每一位游客讲解，游客无法实时获得每一个想要了解的展品详细信息。
（2） 针对感兴趣的展品，游客难以知晓相似的展品所在位置与数量。
* 功能使用场景描述：

（1）用户来到博物馆，专注于展品，不想阅读繁杂的文字，可使用博物馆app进行语音导览交互将文字转为语音。

（2）当用户在逛展区时，想找到某一相似的展品，不用专门找导览人员，可使用博物馆app进行图像搜索，找到同样或相似的展品并找到展品相应位置及相关信息。


*我们使用百度语音交互API，将展品介绍以语音播报形式推送，更好的让用户沉浸与展品欣赏中。避免用户在参观过程中可阅读过多的文字信息，将关注点聚焦在展品本身。同时还具有语音问答功能，用户可以向该软件提问，例如：怎么走到3号展馆？能向我介绍一下编号xxx的展品吗？等等。

APP内储存了博物馆展品图片及信息，利用图像识别API，我们可以为用户进行展品识别，避免某些展品缺失介绍信息影响游客体验，同时还可以分门别类对用户上传展品图片进行推送，为其介绍类似的展品及所在区域。

# 原型：
![语音导览](063ef787d93c5541b375df661367136.png)
![图像识别](575dacb679360d0a99943a5ca8416d2.png)
