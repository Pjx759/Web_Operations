# Web_Operations
# S1.对[WAI指导原则](https://www.w3.org/WAI/tips/writing/)的中文诠释
## 网页编写的可访问性
> 在这个页面会介绍一些基本的注意事项来帮助更好的编写让不同的人群更容易的获取网页的内容。这些技巧能很好的帮助你实现Web Content Accessibility Guidelines (WCAG)的实践要求。跟随这些相关要求的链接，“理解”文档中的详细背景，教程指南，用户案例等。
### 1.提供内容丰富的、独特的页面标题
* 对于每一个网页来说，提供一个简短的标题可以描述页面内容来区分其他的网页。这个页面标题通常是和页面的主要标题是相同的。会将独特的标题放在更靠前的位置；例如把页面的名字放在组织名字的前面。对于属于多步骤过程的页面，要将当前步骤加入页面标题中
* *实例：页面标题*
  * 主页标题：![主页标题](https://github.com/Pjx759/Web_Operations/blob/master/photo/titles/title1.png)
  * 页面名称后接组织名称：![页面标题后接组织名称](https://github.com/Pjx759/Web_Operations/blob/master/photo/titles/title1-2.png)
  * 页面名称中包括流程步骤：![页面名称中包括流程步骤](https://github.com/Pjx759/Web_Operations/blob/master/photo/titles/title1-3.png)  

更多信息
* **WCAG**
  * [页面标题2.4.2](https://www.w3.org/WAI/WCAG21/quickref/#page-titled)([理解2.4.2](https://www.w3.org/WAI/WCAG21/Understanding/page-titled))
---
### 2.使用标题传达页面的内容和页面的结构
* 使用小标题来对相关的段落进行分组，并且清晰简洁的描述每个分组段落。良好的分组标题相当于提供了内容大纲。
  * 使用标题分类相关内容：![标题分类内容](https://github.com/Pjx759/Web_Operations/blob/master/photo/titles/title2.png)  右侧为使用标题正确分类  

更多信息
* **WCAG**
  * [标题和标签2.4.6](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
  * [段落标题2.4.10](https://www.w3.org/WAI/WCAG21/quickref/#section-headings)
  * [信息和关联1.3.1](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
* **用户故事**
  * [用户在屏幕前如何使用标题导航](https://www.w3.org/WAI/people-use-web/user-stories/#accountant)
---
### 3.让链接的文字有意义
* 编写链接文字是可以描述链接目标的内容。要避免使用会产生歧义的文字，例如‘点击此处’或者‘阅读更多’。说明链接目标的相关信息，例如文档的类型和大小，比如‘Proposal Documents(RTF，20MB)’。
  * 使用链接文本描述目标连接内容：![链接举例](https://github.com/Pjx759/Web_Operations/blob/master/photo/titles/title3.png)  右侧为正确描述  

更多信息
* **WCAG**
  * [链接的目的（在文章中）](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-in-context)
  * [链接的目的（仅链接）](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-link-only)
---
### 4.为图像编写有意义的文本替代品
对于每个图像，编写提供图像信息或功能的可选文本。对于纯粹的装饰性图像，不需要编写替代文本。
*示例：使用替代文本传达重要信息*
**无信息的**
为手机充电：使用提供的电缆和电源适配器将手机连接至电源插座。

**图片的替代文本：**“充电电话”
![无信息的](https://github.com/Luojiachunaaa/Web-operation-and-management/blob/master/images/point4.png)

**信息性**
为手机充电：使用提供的电缆和电源适配器将手机连接至电源插座。

**图片的替代文字：**“将电缆插入手机底部边缘。”
![信息性](https://github.com/Luojiachunaaa/Web-operation-and-management/blob/master/images/point4.png)

*替代文本通常是不可见的；它包含在这个示例中只是为了让您可以看到它是什么。*

更多信息
* **WCAG**
    + [非文本内容 1.1.1](https://www.w3.org/WAI/WCAG21/quickref/#non-text-content) ([理解 1.1.1](https://www.w3.org/WAI/WCAG21/Understanding/non-text-content))     
* **辅导（Tutorial**
    + [图片](https://www.w3.org/WAI/tutorials/images/)    
* **用户故事**
    + [描述文本替代项对盲用户的价值](https://www.w3.org/WAI/people-use-web/user-stories/#accountant)
---    
### 5.为多媒体制作文本和标题
对于纯音频内容，比如播客，提供一个文本。对于音频和视频内容，如培训视频，也提供标题。在抄本和标题中包括对理解内容很重要的口语信息和声音，例如，“门吱吱作响”。对于视频抄本，还包括对重要视频内容的描述，例如“Athan离开了房间”。
更多信息
* **WCAG**
    + [标题 (预先录制) 1.2.2](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded) ([理解 1.2.2](https://www.w3.org/WAI/WCAG21/Understanding/captions-prerecorded))
    + [音频描述或媒体替代(预先录制) 1.2.3](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-or-media-alternative-prerecorded) ([理解 1.2.3](https://www.w3.org/WAI/WCAG21/Understanding/audio-description-or-media-alternative-prerecorded))
* **用户故事**
    + [描述字幕如何帮助聋哑学生](https://www.w3.org/WAI/people-use-web/user-stories/#onlinestudent)
---
### 6.提供明确指示
确保说明、指导和错误信息清晰易懂，避免使用不必要的技术语言。描述输入要求，如日期格式。
*示例：说明传达用户应提供的信息*
![](https://github.com/Luojiachunaaa/Web-operation-and-management/blob/master/images/point6.png)
*示例：Error指示问题所在，并可能指示如何解决问题*
1. [用户名“superbear”已在使用中](https://www.w3.org/WAI/tips/writing/#)
2. [密码必须至少包含一个数字]()

更多信息
* **WCAG公司**
    + [标签或说明3.3.2](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions)（[理解3.3.2](https://www.w3.org/WAI/WCAG21/Understanding/labels-or-instructions)）
* **用户故事**
    + [描述帮助有学习困难的人的简单说明](https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant)
---   
### 7.保持内容简洁明了
根据上下文使用简单的语言和格式。
* 写出简短、清晰的句子和段落。
* 避免使用不必要的复杂单词和短语。考虑为读者可能不知道的术语提供词汇表。
* 首次使用时展开首字母缩略词。例如，Web内容可访问性指南（WCAG）。
* 考虑为读者可能不知道的术语提供词汇表。
* 根据需要使用列表格式。
* 考虑使用图像、插图、视频、音频和符号来帮助阐明含义。

*示例：使内容可读和可理解*

**不必要的复杂**

CPP：在发生车辆碰撞的情况下，公司指定的代表将寻求确定属于所有相关方的财产损失的程度和原因。一旦我们的代表获得信息，使我们能够了解因果关系，我们可以或不可能分配适当的金钱补偿。由此产生的决定可能会导致以下选项之一：索赔未经批准，并被指定为拒绝状态；索赔状态模棱两可，在进行进一步处理之前需要其他信息；索赔部分被批准，并分配和签发了减少的付款，或索赔得到完全批准，并分配和签发总索赔付款。
更容易理解
索赔处理程序（CPP）：如果您发生车祸，我们的代理人将进行调查。调查结果将决定任何索赔付款。这可能导致：
* 批准的索赔-全额付款
* 部分批准的索赔-减少付款
* 未定索赔-需要更多信息
* 拒绝索赔-不付款
![](https://github.com/Luojiachunaaa/Web-operation-and-management/blob/master/images/point7.png)

更多信息
* **WCAG公司**
    + [阅读水平3.1.5](https://www.w3.org/WAI/WCAG21/quickref/#reading-level)（[理解3.1.5](https://www.w3.org/WAI/WCAG21/Understanding/reading-level)）
    + [异常词3.1.3](https://www.w3.org/WAI/WCAG21/quickref/#unusual-words)（[理解3.1.3](https://www.w3.org/WAI/WCAG21/Understanding/unusual-words)）
    + [缩略语3.1.4](https://www.w3.org/WAI/WCAG21/quickref/#abbreviations)（[理解3.1.4](https://www.w3.org/WAI/WCAG21/Understanding/abbreviations)）
* **用户故事**
    + [阅读障碍的用户受益于易于阅读的文本](https://www.w3.org/WAI/people-use-web/user-stories/#classroomstudent)
---   
### 了解有关辅助功能的更多信息
这些技巧是您需要考虑的一些事情，以实现web可访问性。以下资源有助于您了解为什么可访问性很重要，以及使残疾人更容易访问web的指导原则。
* [辅助功能介绍](https://www.w3.org/WAI/fundamentals/accessibility-intro/)-介绍辅助功能并提供指向许多有用资源的链接
* [可访问性原则](https://www.w3.org/WAI/fundamentals/accessibility-intro/)-WCAG要求简介
* [残疾人如何使用网络](https://www.w3.org/WAI/people-use-web/)-现实生活中的例子显示了无障碍对残疾人的重要性
* [如何满足WCAG（快速参考)](https://www.w3.org/WAI/WCAG21/quickref/)-所有WCAG要求和技术的可定制参考

**成员及分工：**

1-3点：彭靖茜 181035022

4-7点：罗佳莼 181042166
