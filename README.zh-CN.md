<div align="center">

# project-based-learning 中文文档

[![原项目](https://img.shields.io/badge/原项目-practical--tutorials--project--based--learning-blue?style=flat-square&logo=github)](https://github.com/practical-tutorials/project-based-learning)
[![微信联系](https://img.shields.io/badge/微信-uaycar-brightgreen?style=flat-square&logo=wechat)](#)

</div>

---

> 本文档是 [practical-tutorials/project-based-learning](https://github.com/practical-tutorials/project-based-learning) 官方 README 的中文导览版。原清单体量巨大（收录上千条教程链接），因此本文档完整汉化项目定位、章节结构与使用说明，并为每种语言挑选代表性教程附中文说明；所有英文项目名与链接保持原样，完整清单请以原仓库为准。

**代部署 / 定制服务 / 技术咨询 请添加微信：uaycar**

## 项目定位

原项目是一份"通过做项目来学编程"的教程精选清单：所有教程都要求学习者从零构建一个完整应用，而非零散语法练习。教程按主编程语言划分章节，部分教程会涉及多种技术和语言。想参与维护可直接 Fork 原仓库，贡献规范见其 CONTRIBUTING.md。

## 目录（按语言）

| 章节 | 方向概述 |
|:-----|:---------|
| C/C++ | 操作系统、编译器、数据库、图形学等系统级硬核实战 |
| C# | RPG 游戏、Rogue-like、Xamarin 移动应用 |
| Clojure | Twitter 机器人、拼写检查、JIRA 集成 |
| Dart (Flutter) | 克隆亚马逊、TikTok、WhatsApp 等知名 App |
| Elixir / Erlang / F# | Phoenix 聊天室、短链接服务、多用户聊天室、迷你 Excel |
| Go | 服务器、区块链、Docker 化应用等（见原仓库） |
| Haskell / OCaml / Scala | 函数式语言项目实战（见原仓库） |
| HTML/CSS | 加载动画、计算器、贪吃蛇、React Native 移动端 |
| Java | 解释器、HTTP 服务器、Android 应用、Spring Boot |
| JavaScript | 30 天 30 项目、React/Vue/Angular/Node 全家桶实战 |
| Kotlin | 边做 Android 应用边学 Kotlin |
| Lua (LÖVE) | BYTEPATH 完整游戏开发系列 |
| PHP | Web 应用实战（见原仓库） |
| Python | 爬虫、Web、机器人、数据科学、机器学习 |
| Ruby / Rust / Swift | Web 框架、系统编程、iOS 应用（见原仓库） |
| Additional resources | 附加学习资源 |

## C/C++：系统级硬核实战

原章节最大的亮点是"造轮子"系列，代表性教程：

- **Build an Interpreter**（[craftinginterpreters.com](http://www.craftinginterpreters.com/)）：手写解释器的经典之作，第 14 章起改用 C 实现
- **Write an OS from scratch**（[github.com/tuhdo/os01](https://github.com/tuhdo/os01)）：从零写一个操作系统
- **Building a CHIP-8 Emulator**（[austinmorlan.com](https://austinmorlan.com/posts/chip8_emulator/)）：写一台 CHIP-8 模拟器
- **Write a C compiler**（[norasandler.com](https://norasandler.com/2017/11/29/Write-a-Compiler.html)）：10 部曲，从词法分析一路写到函数与全局变量
- **Writing a Linux Debugger**（[blog.tartanllama.xyz](https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/)）：10 部曲，实现断点、寄存器、堆栈回溯等调试器核心功能
- **Let's Code a TCP/IP Stack**：5 部曲，手写以太网/ARP/IPv4/ICMP/TCP 协议栈
- **Programming concurrent servers**：6 部曲，多线程、事件驱动、libuv 到 async/await 的并发服务器演进
- **Tiny 3D graphics projects**：ssloy 出品的软件渲染、光线追踪系列，几百行 C++ 看懂 OpenGL 原理
- **Build Your Own Redis with C/C++**（[build-your-own.org](https://build-your-own.org/redis/)）：手写一个 Redis

另有：写 Shell、写 FUSE 文件系统、写 Lisp、写哈希表、写简易数据库、写内核与引导程序、500 行代码实现 Linux 容器、写 LC-3 虚拟机、Space Invaders 与俄罗斯方块游戏等。

### Network programming / OpenGL

网络编程与 OpenGL 子章节包含：MQTT Broker 从零实现系列、learnopengl.com 的 2D 打砖块游戏完整教程、Handmade Hero 等。

## C#：游戏与移动端

- **Learn C# By Building a Simple RPG Game**：通过写一个简单 RPG 游戏学 C#
- **Create a Rogue-like game in C#**：用 RogueSharp 写 Rogue-like 游戏
- **Building the CoreWiki**：用 ASP.NET Core + Razor Pages 从零写 Wiki 式内容管理系统

## Dart / Flutter：克隆知名 App

该章节清一色视频教程，通过克隆练手：Amazon Clone（含管理后台）、TikTok Clone、WhatsApp Clone、Netflix Clone、Zoom Clone、Google Docs Clone、Wordle Clone、多人井字棋等十余个项目。

## Elixir / Erlang / F#

- 用 Elixir + Phoenix 写实时聊天室、高性能短链接服务
- ChatBus：用 Erlang/OTP 写第一个多用户聊天室
- **Write your own Excel in 100 lines of F#**：100 行 F# 写一个迷你 Excel

## Java

- **Build an Interpreter**：解释器前半部分（第 4-13 章）用 Java 实现
- 手写简易 HTTP Server、带用户认证的 Spring Boot 应用、Android 手电筒 App（视频）

## JavaScript / HTML+CSS：Web 全栈主战场

入门与原生 JS：

- **Build 30 things in 30 days with 30 tutorials**（javascript30.com）：30 天 30 个原生 JS 项目
- 原生 JS 天气 App、Todo List、贪吃蛇、HTML 计算器

React 专题（子条目最多）：Serverless React 应用、Trello 克隆、Yelp 克隆、Medium 克隆、React + Parcel 写 Chrome 扩展、Puppeteer + Jest 测试 React 应用、React + Firebase 做 Todoist 克隆等。

其他框架与方向：

- **Angular**：Instagram 克隆、支持离线的 Hacker News 客户端、Angular 8 真实世界项目
- **Node.js**：Node + Postgres + Knex 测试驱动开发、Twitter 机器人、GitHub App、职位爬取应用
- **Vue**：Vue 2 + Firebase 15 分钟搭应用、MEVN 全栈系列、Vue + GraphQL + Apollo 写博客
- **Next.js**：官方 App Router 仪表盘教程
- **PWA / 桌面 / 杂项**：三部曲写渐进式 Web 应用、Electron 桌面聊天室、20 行代码写 Web 框架、手写 Redux、手写 Virtual DOM
- **游戏开发**：Phaser 写 2D 打砖块与 Flappy Bird
- **D3.js**：数据可视化与折线图入门

## Kotlin

- **Keddit**：通过开发一个 Reddit 客户端 Android 应用学习 Kotlin

## Lua / LÖVE

- **BYTEPATH**：16 部曲完整游戏开发系列，从游戏循环、房间系统、技能树一路到成品

## Python：方向最全

- **Web Scraping**：Scrapy + MongoDB、Selenium WebDriver、BeautifulSoup 选电影
- **Web Applications**：Flask 巨型教程写微博、Django Girls 写博客、Django + TDD 写 Todo、Docker + Flask + React 微服务、Streamlit 数据应用
- **Bots**：Reddit 机器人、Facebook Messenger 机器人、Telegram 机器人（含 Django 部署）
- **Data Science**：系列视频项目——推特情感分析、推荐系统、股价预测、TensorFlow Deep Dream、遗传算法
- **Machine Learning**：手写线性回归、从零搭神经网络、预测红酒质量、无监督学习入门

## 其他语言

Ruby、Rust、Swift、Go、Haskell、OCaml、PHP、Scala 等章节同样收录了大量从零实战项目（Rust 写 Web 应用、Swift 写 iOS 应用等），详见原仓库对应章节。

## Additional resources

原清单末尾还有附加学习资源章节，汇总更多练习平台与项目灵感来源。

## 使用建议

1. 先选定一门主力语言，从该章节挑一个"跳一跳够得着"的项目
2. 坚持"不看答案先自己写"，卡住再回看教程对应步骤
3. 做完一个项目就推到自己 GitHub，形成作品集
4. 教程链接失效时以原仓库最新版为准（原项目有自动化链接巡检）

---

> 本文档为中文翻译导览，内容版权归 [practical-tutorials/project-based-learning](https://github.com/practical-tutorials/project-based-learning) 原项目作者所有，遵循其原始许可证。

**代部署 / 定制服务 / 技术咨询 请添加微信：uaycar**

**如果觉得有用，请给原项目点个 Star！** ⭐
