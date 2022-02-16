# Uncle Kaimo's Cabin - 凯默叔叔的小屋

## 介绍

❤️🧡💛💚💙💜欢迎来到凯默叔叔的小屋💜💙💚💛🧡❤️。

[总目录导航](https://github.com/kaimo313/uncle-kaimo-cabin/blob/main/docs/roadmap.md)

## 在线阅读地址

Github Pages 阅读：[https://kaimo313.github.io/uncle-kaimo-cabin/#/](https://kaimo313.github.io/uncle-kaimo-cabin/#/)

## docsify 命令操作

该项目采用了 [docsify](https://docsify.js.org/#/zh-cn/quickstart) 搭建。

### 全局安装脚手架

```bash
npm i docsify-cli -g
```

安装好 `docsify-cli` 可以用下面命令初始化项目

```bash
docsify init ./docs
```

### 本地预览

```bash
docsify serve ./docs
```

## docsify 插件

[【docsify-tabs】：A docsify.js plugin for rendering tabbed content from markdown.](https://jhildenbiddle.github.io/docsify-tabs/#/)

```md
<!-- tabs:start -->
#### **电影榜单**
#### **读书榜单**
#### **音乐榜单**
<!-- tabs:end -->
```

[【docsify-example-panels】：A docsify.js plugin for rendering example panels content from markdown.](https://vagnerdomingues.github.io/docsify-example-panels/#/)

```md
<!-- panels:start -->
<!-- div:left-panel -->
<!-- div:right-panel -->
<!-- panels:end -->
```

[【docsify-plugin-flexible-alerts】：This docsify plugin converts blockquotes into beautiful alerts.](https://github.com/fzankl/docsify-plugin-flexible-alerts)

```md
> [!NOTE]
> An alert of type 'note' using global style 'callout'.

> [!TIP]
> An alert of type 'tip' using global style 'callout'.

> [!WARNING]
> An alert of type 'warning' using global style 'callout'.

> [!ATTENTION]
> An alert of type 'attention' using global style 'callout'.
```
