---
title: 使用Notebook LM制作属于自己的知识机器人
date: 2025-12-04 02:07:23 +0000
categories: [Blogging, NotebookLM]
author: SZE Cary
tags: [NotebookLM]
---

这篇教程是根据11份的NotebookLM进行重置，重置的版本会增加使用案例，实际去部署使用NotebookLM, 利用它来不是一个问答机器人

## 前言
Gemini在香港版本的workspace是可以访问的，但是NotebookLM就不能访问，很简单，只需要VPN（梯子）就可以访问到了。所以，哪里有便宜的VPN呢？

直接使用Surfshark VPN（最推荐使用）一年的价格便宜，好像400HKD，特别便宜

注意，如果是从第三方平台购买的1年的学生优惠账号，对于这些没给钱的账号，Google会一直提示验证账号，有几率追加封号，原因是该机器人注册了此账号。这种账号当初就是机器人所注册的。所以，IP纯净度只是Google检测风险的一种手段，不是唯一手段，人家想封你购买的Gmail号也有别的手段。

## 打开NotebookLM
利用VPN，访问：(https://notebooklm.google/)

![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 211327.png){: width="972" height="589" }


## 创建NotebookLM
直接点击建立新的笔记本
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 211703.png){: width="972" height="589" }
然后上传来源，这里可以可以是所有文档都可以

## 寻找来源
假设我有正在学习一个科目，名字叫Research Methodology in Applied Sciences, 我想建立一个知识库，所以我们可以下载它的所有课件
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 212100.png){: width="972" height="589" }

然后将所有的课件全部放到NotebookLM, 我们一次Notebook最多可以上传300份参考资料
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 212417.png){: width="972" height="589" }
这里NotebookLM会自动总结你所有上传的文件，需要花一点时间甚至更久，让它去思考内容，等待完成会出现
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 212953.png){: width="972" height="589" }

## 设定对话
这里可以设定它的语气
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 212736.png){: width="972" height="589" }

## 设置欢迎词
当用户开启你的Notebook LM的时候，LM会自动发送一条信息
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 213529.png){: width="972" height="589" }

Workspace版本不支持直接将笔记本公开分享，只能预览并对话
个人版本可支持公开分享，如果是Google Workspace for Eduation版本可以直接共享到学生中

输入一些欢迎词
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 213837.png){: width="972" height="589" }
编辑完点击储存


## 工作室
工作室有8个功能，当然你可以直接对话

### 心智图
首先先介绍心智图，LM会生成心智图，不过这需要很长的时间
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 214255.png){: width="972" height="589" }
然后就会生成思维导图，然后这些你可以点击按钮张开，点击右上角的按钮图标可以下载思维导图
这很类似于学习大纲，帮你生成学习步骤

### 影片摘要
LM生成一条影片，但是生成的时间会更长，来源越多，生成的时间就越久

### 语音摘要
LM会生成一条AI的播客，有2位主持人一问一答，来源越多，生成对策时间就越久

### 测验
LM会生成题库，有些注意事项要说一下
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 215232.png){: width="972" height="589" }
你看到21个来源只生成了12条题目，很明显是不利于复习或者生成题目，所有我们要勾选自己想要复习的课题

我们点击测量的右边的铅笔键，看到了吗？
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 215726.png){: width="972" height="589" }
这里可以调整题目数量，难度，下面的提示词可以修改复习范围，然后重新生成就可以

### 学习卡
LM会生成学习卡，帮助你学习和强化概念
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 214915.png){: width="972" height="589" }

### 资讯图表
LM会生成图表，但是由于是学习知识，不需要用到
这个会用到的地方就是用于销售场景或者是调查问卷这类地方

### 简报
LM会生成幻灯片，但是这次教程不适用，因为我们有足够的来源

### 报告
LM会生成报告，但是这次教程不适用，用于调查问卷或者是销售场景

## 对话
接下来，我们可以尝试对话，可以询问
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 220343.png){: width="972" height="589" }

然后它的回答
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 220542.png){: width="972" height="589" }

如果你觉得它的回复很有用，想保存下来，点击“储存至记事”，就可以保存，请注意：对话记录不会保留，所以要自己手动保存

**请注意，Workspace的版本不能分享整个Notebook，只能分享聊天框对话**
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 220826.png){: width="972" height="589" }

如果叫它生成学习卡就会出现这类情况
![Desktop View](/assets/picture/Using-NotebookLM/2025-12-04 221124.png){: width="972" height="589" }

只能生成对话，不能生成多媒体，所以不能分享笔记本给公众

## 用途
NotebookLM可以用于学习用途，比如讲解Lecture的知识，生成Lecture的闪卡和最后的测验，这种对于学生来说非常方便去准备考试或者学习新技能

NotebookLM也可以用于视频创作，指定自己的知识来源，生成一份摘要，然后可以变成Podcast播客或者Video视频

NotebookLM也用于团队协作，建立企业自己最简单的聊天机器人，当然，这是非常简单的机器人

## 总结
NotebookLM和Gemini网页版其实各有千秋，都有优点和缺点，所以当要处理更多来源的时候请使用NotebookLM。
