# 一个 PHP 菜鸟的心路历程

[![Hugo](https://img.shields.io/badge/Hugo-%5E0.134.1-ff4088?style=flat&logo=hugo)](https://gohugo.io/)
[![Hugo build and deploy](https://github.com/w2lz/hugo-blog/actions/workflows/deploy.yml/badge.svg?branch=main)](https://github.com/w2lz/hugo-blog/actions/workflows/deploy.yml)
[![GitHub commit activity (main)](https://img.shields.io/github/commit-activity/m/w2lz/hugo-blog/main?style=flat)](https://github.com/w2lz/hugo-blog/commits/main)

> 站名“一个 PHP 菜鸟的心路历程”，主要是为了纪念刚入行的日子。

博客基于 [Hugo](https://github.com/gohugoio/hugo) 和 [FixIt](https://github.com/Lruihao/FixIt) 搭建，建站的初衷不是为了炫耀所知，而是记录无知。

博客内容主要以 Web 后端开发方向为主，分享一些有趣程序、技巧、开发教程、心情和学习记录等。

你可以通过我的[微信公众号](https://blog.yingnan.wang/images/qr-wx-mp.webp "关注「一个 PHP 菜鸟的心路历程」公众号")、[GitHub](https://github.com/w2lz/hugo-blog "Watch on GitHub") 或 [RSS](http://blog.yingnan.wang/index.xml) 来订阅本博客。

![blog-preview](/assets/images/apple-devices-preview.webp)

## Content

- [归档](https://blog.yingnan.wang/archives/)
- [分类](https://blog.yingnan.wang/categories/)
- [合集](https://blog.yingnan.wang/collections/)
- [标签](https://blog.yingnan.wang/tags/)
  
## Source

博客相关源码：

- [Hugo FixIt 相关](https://github.com/hugo-fixit)
- [更多](https://github.com/w2lz?tab=repositories)

## [Roadmap](https://github.com/users/w2lz/projects/1)

## Project setup

本博客已部署到 [GitHub Pages](https://github.com/w2lz/w2lz.github.io)，工作流如下图所示：

![blog-flow](/assets/images/blog-flow.png)

```bash
▸ .github/       # GitHub configuration
▸ .scripts/      # custom scripts
▸ .shell/        # shell commands for hugo project, entrance: hugo_main.sh
▸ archetypes/    # page archetypes (like scaffolds of archetypes)
▸ assets/        # css, js, third-party libraries etc.
▸ config/        # configuration files
▸ content/       # markdown files for hugo project
  ▸ private/     # private submodule for encrypted content
▸ data/          # blog data (allow: yaml, json, toml), e.g. friends.yml
▸ public/        # build directory
▸ static/        # static files, e.g. favicon.ico
▸ themes/        # theme submodules
```

### System requirements

- [Go](https://go.dev/dl/)
- [Hugo](https://gohugo.io/installation/): >= 0.134.1 (extended version)

### Clone

首先点上 Star 😜，然后下载源码：

```bash
git clone --recursive git@github.com:w2lz/hugo-blog.git && cd hugo-blog
```

下载源码后，可以通过下面的方式启动这个博客。

### Hugo

```bash
# Development environment
hugo server --disableFastRender --navigateToChanged --bind 0.0.0.0
# Production environment
hugo server --disableFastRender --navigateToChanged --environment production --bind 0.0.0.0
```

## License

[![Content License](https://img.shields.io/badge/license-CC_BY--NC--SA_4.0-blue?style=flat)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![License](https://img.shields.io/github/license/w2lz/hugo-blog?style=flat)](https://github.com/w2lz/hugo-blog/blob/main/LICENSE)

- 此存储库中的文本、图像和视频等内容采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可
- 此存储库中的代码采用 [MIT](https://github.com/w2lz/hugo-blog/blob/main/LICENSE) 许可
- _`content/private` 目录不在任何许可范围内_

## Author

[w2lz](https://github.com/w2lz "在 GitHub 上关注我")
