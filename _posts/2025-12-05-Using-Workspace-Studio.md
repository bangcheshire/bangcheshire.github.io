---
title: 探索Workspace studio，生成一个每日新闻机器人
date: 2025-12-05 02:07:23 +0000
categories: [Blogging, Workspace-studio]
author: SZE Cary
tags: [Workspace-studio]
---

Google在昨天发布了一个全新的工具，Workspace Studio，这个工具就是类似于Microsoft Powerautomate，它是一个AI Agent, 能够帮助企业能在低成本的部署AI，不需要学习成本

来自Google的介绍
<https://workspace.google.com/studio/>

所以我们可以仔细去探索新功能

## 首页
这是Workspace Studio的首页
![Desktop View](/assets/picture/Using-Workspace-studio/2025-12-05 190527.png){: width="972" height="589" }

可以看到Studio已经预设了不同的Agent，有追踪新的需求，还有分析业务，然后还有总结会议发送到指定的邮件等等

到时候我可能会生成几个案例去帮助大伙怎么去应用，先学个最简单的，自动发送邮件

## 邮件Agent
![Desktop View](/assets/picture/Using-Workspace-studio/2025-12-05 190601.png){: width="972" height="589" }
你看到邮件有很多不同的Agent,有自动提醒的，有自动发送，也有总结文件，不过我们身为个人不可能拥有这么多的案例。所以我们就先做个最简单的总结每日新闻的Agent

## 每日总结新闻
![Desktop View](/assets/picture/Using-Workspace-studio/2025-12-05 191411.png){: width="972" height="589" }
我们点击Get news headlines summarized daily

### 设置定时器
点击完你就会看到
![Desktop View](/assets/picture/Using-Workspace-studio/2025-12-05 191539.png){: width="972" height="589" }
这里可以设置定时器，自由去设置，可以每周，每月，每天

### 询问Gemini
![Desktop View](/assets/picture/Using-Workspace-studio/2025-12-05 192216.png){: width="972" height="589" }
这里可以修改内容，对于新人来说，Prompt（提示词）最头疼的问题，其实不难，直接在gemini网页端<https://gemini.google.com/app> 撰写就行。

![Desktop View](/assets/picture/Using-Workspace-studio/2025-12-05 193059.png){: width="972" height="589" }
这里Add Variable，可以添加变量，但是这篇教程暂时不用，之后我再来补回来

### 发送邮件
然后到第三步，将邮件发送到指定的邮箱
![Desktop View](/assets/picture/Using-Workspace-studio/2025-12-05 193429.png){: width="972" height="589" }

To是收件人，Subject是标题，Message就是刚才Gemini生成的消息，这里是用Variable去串联的，然后完成后点击Test Run先测试效果，如果没问题了就是Turn On,就可以每天推送新闻了

## 效果图
![Desktop View](/assets/picture/Using-Workspace-studio/2025-12-05 194237.png){: width="972" height="589" }

## 总结
由于这个功能是昨天才推出的，所以都在处于探索阶段，这个只是其中的一个最简单实现的方法，假若企业或者学校有更多使用Google Workspace，Workspace studio的功能就会越强大，下一篇可能还会基于studio开发新的适用于企业的教程
