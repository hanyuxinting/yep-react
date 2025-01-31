---
category: Layout
title: 列表项
---

适用 App 规范的列表项组件

<DEMO>

Cell

| 参数      | 说明            | 类型   | 默认值   |
| --------- | --------------- | ------ | -------- |
| prefixCls | 组件 class 前缀 | string | Yep-cell |
| style     | 组件样式        | object | {}       |
| className | 组件额外样式    | string | -        |

Cell.Item

| 参数        | 说明                                     | 类型        | 默认值        |
| ----------- | ---------------------------------------- | ----------- | ------------- |
| prefixCls   | 组件 class 前缀                          | string      | Yep-list-item |
| style       | 组件样式                                 | object      | {}            |
| className   | 组件额外样式                             | string      | -             |
| label       | 左侧标题                                 | string/node | -             |
| icon        | 是否显示图标                             | boolean     | true          |
| align       | 子元素垂直对齐，可选`top`,`middle`       | String      | `middle`      |
| onClick     | 点击事件的回调函数                       | (): void    | 无            |
| wrap        | 是否换行，默认情况下，文字超长会被隐藏， | Boolean     | `false`       |
| activeStyle | 自定义 active 的样式                     | Object      | -             |

Cell.Brief 辅助说明

| 参数      | 说明            | 类型   | 默认值   |
| --------- | --------------- | ------ | -------- |
| prefixCls | 组件 class 前缀 | string | Yep-list |
| style     | 组件样式        | object | {}       |
| children  | 辅助说明文本    | string | -        |
