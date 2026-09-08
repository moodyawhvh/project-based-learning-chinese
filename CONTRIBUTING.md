> 🌐 本文档由 [practical-tutorials/project-based-learning](https://github.com/practical-tutorials/project-based-learning) 翻译,英文原版见原项目。

# 贡献指南

在提交 Pull Request 之前,请确认以下几点:

- 你想添加的教程尚不存在(请在 README.md 中搜索该 URL 和标题)。
- 你的教程被正确放置在对应的语言/技术分类下。
- 教程必须是免费开放的——不能有付费墙、登录墙,也不得强制订阅邮件列表。
- 教程必须是项目实战型的——读完之后,读者能构建出一个完整、可运行的作品(而不只是概念讲解)。
- 如果你是教程作者本人,或与作者/网站存在关联,请在 Pull Request 中说明。
- Pull Request 的标题必须具有描述性。
- 如果你的教程所用语言/技术分类尚不存在,欢迎在目录中新建一个条目。
- 请为每个教程单独提交一个 Pull Request。
- 请使用以下格式:`- [标题](教程链接)`。
- 如果你的教程是多篇系列,请使用以下格式:
  ```
  - 标题
    - [第 1 部分](第一部分链接)
    - [第 2 部分](第二部分链接)
  ```
- 检查拼写和语法。
- 清除所有行尾多余空白。
- 链接必须直达教程页面——禁止使用短链接。

在发起 Pull Request 之前,请在仓库根目录本地运行校验器:

```
python3 scripts/check_readme.py lint
```

它必须以状态码 0 退出。校验器会检查上述规范、目录(Table of Contents),以及重复/被缩短的 URL。

CI 还会检查你添加的链接是否可访问。部分网站(Medium、Reddit、LinkedIn、Udemy 及类似站点)会拦截自动检查,因此会显示"无法验证"(could not verify)而不是构建失败——这是正常现象,无需修复。

感谢你的建议!如果你认为本指南还有任何可以改进的地方,请通过 <tuvtran97@gmail.com> 联系我。
