# JekyllNet

![JekyllNet social preview](https://raw.githubusercontent.com/JekyllNet/JekyllNet/main/docs/assets/brand/social-preview.png)

![JekyllNet lockup](https://raw.githubusercontent.com/JekyllNet/JekyllNet/main/docs/assets/brand/jekyll-net-lockup.svg)

**Jekyll-style Static Site Generator for .NET**  
**用 C# 重建 Jekyll / GitHub Pages 风格站点生成体验**

Lightweight, testable, GitHub-Pages-shaped static publishing for .NET teams.  
面向 .NET 团队的轻量、可测试、贴近 GitHub Pages 心智模型的静态站点生成器。

[![Repo](https://img.shields.io/badge/repo-JekyllNet%2FJekyllNet-111827?style=flat-square)](https://github.com/JekyllNet/JekyllNet)
[![Site](https://img.shields.io/badge/site-jekyllnet.help-0f766e?style=flat-square)](https://jekyllnet.help)
[![NuGet Version](https://img.shields.io/nuget/v/JekyllNet?style=flat-square&label=NuGet)](https://www.nuget.org/packages/JekyllNet)
[![NuGet Downloads](https://img.shields.io/nuget/dt/JekyllNet?style=flat-square&label=Downloads)](https://www.nuget.org/packages/JekyllNet)
[![Action v2](https://img.shields.io/badge/action-v2-2563eb?style=flat-square)](https://github.com/JekyllNet/action/tree/v2)
[![CI](https://img.shields.io/github/actions/workflow/status/JekyllNet/JekyllNet/ci.yml?branch=main&label=CI&style=flat-square)](https://github.com/JekyllNet/JekyllNet/actions/workflows/ci.yml)

---

## Intro | 简介

**EN**  
JekyllNet is a .NET 10 static site generator that rebuilds practical Jekyll and GitHub Pages workflows in C#, including build, watch, serve, pagination, Sass, multilingual docs, and reusable GitHub Actions.

**中文**  
JekyllNet 是一个基于 .NET 10 的静态站点生成器，用 C# 重新实现 Jekyll / GitHub Pages 常用工作流，覆盖构建、监听、预览、分页、Sass、多语文档与可复用 GitHub Action。

## Highlights | 本次更新

- 发布 `v0.2.0`，补齐完整使用说明、发布新闻与双语文档入口
- GitHub Action 已发布 `v2` 标签，默认安装 `JekyllNet 0.2.0`
- 文档站已重排为更清晰的首页、导航、博客、新闻结构
- 主题 Pages 构建工作流已统一切换到 `JekyllNet/action@v2`

## Quick Facts | 当前信息

| Item | Value |
| --- | --- |
| Website | [jekyllnet.help](https://jekyllnet.help) |
| Repository | [JekyllNet/JekyllNet](https://github.com/JekyllNet/JekyllNet) |
| NuGet latest | [`0.2.0`](https://www.nuget.org/packages/JekyllNet/0.2.0) |
| NuGet downloads | `0` total downloads as of 2026-03-29 |
| GitHub Action | [`JekyllNet/action@v2`](https://github.com/JekyllNet/action/tree/v2) |
| Runtime | `.NET 10` |

## Tested Themes | 已测试主题

以下主题已进入我们的构建或兼容性验证范围：

- [just-the-docs](https://github.com/JekyllNet/just-the-docs)
- [minimal-mistakes](https://github.com/JekyllNet/minimal-mistakes)
- [al-folio](https://github.com/JekyllNet/al-folio)
- [jekyll-theme-chirpy](https://github.com/JekyllNet/jekyll-theme-chirpy)
- [jekyll-TeXt-theme](https://github.com/kitian616/jekyll-TeXt-theme)

## What You Can Do | 你现在可以做什么

```bash
# install
dotnet tool install --global JekyllNet --version 0.2.0

# build
jekyllnet build --source ./my-site

# preview
jekyllnet serve --source ./my-site
```

## Links | 入口

- Docs / 文档: [jekyllnet.help](https://jekyllnet.help)
- NuGet: [JekyllNet package](https://www.nuget.org/packages/JekyllNet)
- Action: [JekyllNet/action](https://github.com/JekyllNet/action)
- Source: [JekyllNet/JekyllNet](https://github.com/JekyllNet/JekyllNet)

Built with .NET 10 · GitHub Pages style workflows · MIT License
