---
title: 架构预览
intro: '您可以在即将推出的功能和 {% data variables.product.prodname_dotcom %} GraphQL 架构变更添加至 {% data variables.product.prodname_dotcom %} GraphQL API 之前预览它们。'
redirect_from:
  - /v4/previews
versions:
  fpt: '*'
  ghec: '*'
  ghes: '*'
  ghae: '*'
topics:
  - API
---

## 关于架构预览

在预览期间，我们可以根据开发者的反馈更改某些功能。 如果我们要执行变更，将在[开发者博客](https://developer.github.com/changes/)上宣布消息，不会事先通知。

要访问架构预览，需要在 `Accept` 标头中为您的请求提供自定义[媒体类型](/rest/overview/media-types)。 每个预览的功能文档可指定要提供的自定义媒体类型。

{% note %}

**注：**目前无法通过 Explorer 访问预览下的 GraphQL 架构成员。

{% endnote %}
