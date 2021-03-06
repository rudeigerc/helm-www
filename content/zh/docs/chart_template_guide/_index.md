---
title: "Chart 模板指南"
weight: 5
---

# Chart模板开发者指南

该指南提供Helm Chart模板的介绍，重点强调模板语言。

模板会生成manifest文件，使用Kubernetes可以识别的YAML格式描述。我们会看到模板是如何结构化的，
它们如何被使用，如何编写Go模板，以及如何调试你们的工作内容。

该指南聚焦于以下概念：

- Helm模板语言
- values值的使用
- 使用模板工作的技术点

该指南面向学习Helm模板语言的来龙去脉。其他指南提供介绍性资料，示例和最佳实践。
