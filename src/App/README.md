﻿# 主项目介绍

这是哔哩应用的主项目，对于 UWP 应用来说，不需要额外的打包项目。

该项目主要用于处理 UI，是应用架构中的最上层，和用户直接交互。

项目中包含的内容主要分为：

- 页面
- 控件
- 资源，包括样式资源和文本资源
- 辅助工具，包括各种数据转换器、UI 扩展、行为(Behavior) 等

一般来说，对于需要复用且样式可能更改的控件，推荐使用 `TemplateControl` 模板，而简单的控件集合体则可以使用 `UserControl` 模板。