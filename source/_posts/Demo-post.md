---
title: Hello World
category: Quick Start
tags: [Hexo, Setup]
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

| 名称 | 价格($/件) | 库存 | 发布时间 | 链接 | 截止日期 | 颜色 | 款式(儿童，成人) | 设计者 |
| :--: | :--------: | :--: | :------: | :--: | :------: | :--: | :--------------: | :----: |
|  ·   |     ·      |  ·   |    ·     |  ·   |    ·     |  ·   |        ·         |   ·    |
|  ·   |     ·      |  ·   |    ·     |  ·   |    ·     |  ·   |        ·         |   ·    |
|  ·   |     ·      |  ·   |    ·     |  ·   |    ·     |  ·   |        ·         |   ·    |

- 早餐
  - 煎蛋：鸡蛋是早餐中的主角，煎蛋可以是早晨清新的开始。
  - 烤面包：香脆的烤面包搭配牛油和果酱，是简单又美味的早餐选择。
- 午餐
  - 意大利面：色香味俱佳的意大利面，是午餐中的经典美食。

> 阳光透过窗子，折射出一个个**耀斑**， 简打开窗子，温暖的清风扑面而来，携卷着淡淡的花香，微微卷起脸庞*细碎的鬓角*，像是一位即将走向成熟的少女，在耳边低低地浅吟。 —— 《消失》

# Heading 1

这个函数依然被命名为 `convert-string-to-color`，并接受两个参数：`str` 是要转换的字符串，`default-color` 是默认的颜色变量。在这个版本中，`default-color` 的值是 `#ff00ff`，而 `theme-color` 的值是 `#00ffff`。

## Heading 2

函数的实现方式是，首先使用 `convert` 函数将传递给它的字符串转换为颜色类型的变量。如果字符串无法转换为颜色类型的变量，函数将返回**默认颜色变量**。如果字符串的类型是 `"default"` 或 `"theme"`，函数将分别返回默认颜色或主题颜色。如果字符串的类型是其他类型（如数字、*布尔值*等），函数将直接返回默认颜色变量。

### heading 3

示例用法将字符串 `"red"` 作为参数传递给函数，并提供了另一个颜色变量 `#ff0000` 作为默认颜色。因为字符串的值可以转换成颜色类型的变量，所以函数返回转换后的颜色变量，即 `red` 的颜色类型的变量。

#### heading 4

总的来说，`$color = convert("theme", color) || $minorColor` 的返回值取决于两个操作数的真假值。如果第一个操作数为真值，那么 `||` 运算符会直接返回第一个操作数的值，忽略第二个操作数。如果第一个操作数为假值，那么 `||` 运算符会返回第二个操作数的值，忽略第一个操作数。

##### heading 5

在这些示例中，我们使用 `convert` 函数将一个类型的值转换为另一个类型。可以根据具体情况选择要转换的类型，并将要转换的值作为参数传入函数中。使用 `convert` 函数可以方便地进行类型转换，帮助我们更好地操作和处理不同类型的数据。

###### heading 6

是的，GitHub 仓库的默认权限设置是允许所有人 clone 和 pull，但普通用户不能 push。如果需要对仓库进行更细粒度的权限控制，可以在仓库的“Settings”页面中的“Manage access”选项中添加或删除用户并设置相应的权限。