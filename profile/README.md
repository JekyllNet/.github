<p align="center">
  <img src="https://raw.githubusercontent.com/JekyllNet/JekyllNet/main/docs/assets/brand/jekyll-net-lockup.svg" alt="JekyllNet" width="480">
</p>

<p align="center">
  <strong>Jekyll-style Static Site Generator for .NET</strong><br>
  用 C# 重现 Jekyll / GitHub Pages 行为，面向 .NET 生态。
</p>

<p align="center">
  <a href="https://github.com/JekyllNet/JekyllNet/actions"><img src="https://img.shields.io/github/actions/workflow/status/JekyllNet/JekyllNet/ci.yml?branch=main&label=CI&style=flat-square" alt="CI"></a>
  <a href="https://www.nuget.org/packages/JekyllNet"><img src="https://img.shields.io/nuget/v/JekyllNet?style=flat-square&label=nuget" alt="NuGet"></a>
  <a href="https://github.com/JekyllNet/JekyllNet/blob/main/LICENSE"><img src="https://img.shields.io/github/license/JekyllNet/JekyllNet?style=flat-square" alt="License"></a>
</p>

---

## 关于 JekyllNet

**JekyllNet** 是一个用 C# 编写的 Jekyll 风格静态站点生成器，目标是逐步覆盖 Jekyll / GitHub Pages 的常用行为，同时保持代码库可测试、可维护、可迭代。

### ✨ 核心能力

| 能力 | 状态 |
|------|------|
| `_config.yml` + YAML Front Matter | ✅ |
| Markdown → HTML | ✅ |
| `_layouts` 嵌套 / `_includes` / `_data` | ✅ |
| `_posts` / `collections` / `tags` / `categories` | ✅ |
| Liquid 标签与常用 filters | ✅ |
| Sass / SCSS 编译 | ✅ |
| `_config.yml defaults` | ✅ |
| `drafts` / `future` / `unpublished` 开关 | ✅ |
| Pagination | ✅ |
| AI 多语言翻译管线（OpenAI / DeepSeek / Ollama） | ✅ |
| dotnet tool 全局安装 | ✅ |
| 可复用 GitHub Action | ✅ |

### ⚡ 快速开始

```bash
# 全局安装
dotnet tool install --global JekyllNet

# 构建站点
jekyllnet build --source ./my-site

# 本地预览
jekyllnet serve --source ./my-site
```

### 🤖 AI 翻译

在 `_config.yml` 中配置后，构建时自动生成多语言页面：

```yaml
ai:
  provider: openai
  model: gpt-4o-mini
  api_key_env: OPENAI_API_KEY
  translate:
    targets: [en, fr, ja]
```

支持 OpenAI、DeepSeek、Ollama 及任意 OpenAI-compatible 服务商。

### 📦 仓库

| 仓库 | 说明 |
|------|------|
| [JekyllNet/JekyllNet](https://github.com/JekyllNet/JekyllNet) | 核心引擎、CLI、文档 |

---

<p align="center">
  <sub>Built with .NET 10 · MIT License</sub>
</p>
