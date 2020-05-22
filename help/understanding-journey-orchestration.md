---
title: 了解旅程安排
description: 了解旅程编排的概念、它支持的使用案例类型以及旅程编排工作方式的关键元素。
feature: Journey Orchestration
topics: Introduction
kt: 2773
audience: user, developer
doc-type: video
activity: understand
translation-type: tm+mt
source-git-commit: 795b30fe984b7fe715789144e8c421028d7d32ac
workflow-type: tm+mt
source-wordcount: '326'
ht-degree: 0%

---


# 理解 [!UICONTROL Journey Orchestration]

## 简介 [!UICONTROL Journey Orchestration]

[!UICONTROL Journey Orchestration] 使您能够利用存储在事件或数据源中的情境数据构建实时业务流程使用案例。

[!UICONTROL Journey Orchestration] 是与Adobe Experience Platform集成的应用程序服务。 它提供了一个智能、开放的生态系统，通过可扩展的、基于事件的参与来激活所有相关实时数据，涵盖从营销、运营到服务的所有渠道。 [!UICONTROL Journey Orchestration] 可以利用Adobe Experience Platform和任何外部投放系统的任何数据来创建和交付引人入胜的体验。

以下视频介绍

* The concept of [!UICONTROL Journey Orchestration]
* 它启用的用例类型
* 工作方式的关键要 [!UICONTROL Journey Orchestration] 素

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12)

## 如何配置旅程

建筑旅程的准备工作主要包括：

1. [配置流事件](/help/configuring-journey-orchestration/configure-streaming-events.md) -此配置是必选的，因 [!UICONTROL Journey Orchestration] 为设计为监听事件。
2. [配置数据源](/help/configuring-journey-orchestration/configure-data-sources.md) -如果您的旅程仅利用来自事件有效负荷的本地数据，则不需要此配置。
3. [配置自定义操作](/help/configuring-journey-orchestration/configure-actions.md): 如果要使用任何第三方提供商提供的服务，可通过JSON格式有效负荷调 [!DNL REST API] 用该服务，则此为必需

>[!NOTE]
>这些配置步骤需要技术知识。 您需要熟悉体验数 [据模型(XDM)](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html), [以及如何构建XDM体验事件模式](https://docs.adobe.com/content/help/en/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html)。

## 如何创建、发布和分析旅程

1. [创建旅程](/help/create-a-journey.md)
2. [验证和发布旅程](/help/validate-and-publish-a-journey.md)
3. [通过报告工具分析旅程](/help/analyze-a-journey-via-reporting-tools.md)

## 其他资源

* [旅程编排帮助中心](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Adobe Experience Platform教程](https://docs.adobe.com/content/help/en/platform-learn/tutorials/overview.html)
* [如何找到旅程编排帮助](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK - Launch](https://docs.adobe.com/content/help/en/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Adobe Experience Platform定位服务](https://docs.adobe.com/content/help/en/places/using/home.html)
