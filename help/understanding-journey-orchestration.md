---
title: 了解 Journey Orchestration
description: 了解 Journey Orchestration 的概念、支持的用例类型以及 Journey Orchestration 如何工作的关键要素。
feature: Overview
topics: Introduction
jira: KT-2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
exl-id: db4f69bb-183c-4376-9791-eb6b1f78ab32
source-git-commit: 9db2765ee5e9520280711a6b1fe3c618963f6f87
workflow-type: ht
source-wordcount: '280'
ht-degree: 100%

---

# 了解 [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] 使您可以利用存储在事件或数据源中的上下文数据构建实时编排用例。

## [!UICONTROL Journey Orchestration] 简介

[!UICONTROL Journey Orchestration] 是与 Adobe Experience Platform 集成的应用程序服务。它提供一个智能、开放的生态系统，通过可扩展的、基于事件的参与来激活所有相关实时数据，涵盖从营销、运营到服务的所有渠道。[!UICONTROL Journey Orchestration] 可以利用 Adobe Experience Platform 和任何外部投放系统的任何数据来创建和提供引人入胜的体验。

以下视频介绍

* [!UICONTROL Journey Orchestration] 的概念
* 它支持的用例类型
* [!UICONTROL Journey Orchestration] 工作原理的关键要素

>[!VIDEO](https://video.tv.adobe.com/v/29307?learn=on){transcript=true}

## 如何配置旅程

构建旅程的准备工作主要包括：

1. [配置流事件](/help/configuring-journey-orchestration/configure-streaming-events.md) - 此配置是必需的，因为 [!UICONTROL Journey Orchestration] 设计为监听事件。
1. [配置数据源](/help/configuring-journey-orchestration/configure-data-sources.md) - 如果您的历程只利用来自事件有效负载的本地数据，则不需要此配置。
1. [配置自定义操作](/help/configuring-journey-orchestration/configure-actions.md)：如果要使用任何第三方提供商提供的服务（可通过带有 JSON 格式有效负载的 [!DNL REST API] 调用），则此配置是必需的

>[!NOTE]
>
>这些配置步骤需要技术知识。您需要熟悉 [体验数据模型 (XDM)](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=zh-Hans) 和[如何构建 XDM 体验事件架构](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=zh-Hans)。

## 如何创建、发布和分析历程

1. [创建历程](/help/building-a-journey/creating-a-journey.md)
1. [验证和发布历程](/help/validate-and-publish-a-journey.md)
1. [通过报告工具分析历程](/help/analyze-a-journey-via-reporting-tools.md)

## 其他资源

* [Journey Orchestration 帮助中心](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hans)
* [Adobe Experience Platform 教程](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=zh-Hans)
* [如何查找有关 Journey Orchestration 的帮助](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform 移动端软件包 - 发布](https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/overview.html?lang=zh-Hans)
* [Adobe Experience Platform 位置服务](https://experienceleague.adobe.com/docs/places/using/home.html?lang=zh-Hans)
