# Slidev 模板项目

这是一个基于 `slidev-theme-prussianblue` 主题项目的模板项目，使用 Slidev 工具，可以快速地使用 Markdown 和 Vue.js 创建演示文稿。

## 背景信息

Slidev 是一种现代化的演示文稿创建工具，使用 Vue.js 构建。它支持在 Markdown 文件中导入自定义 Vue 组件，然后将这些文件转换为 PDF 或 PPT 格式。这使得它成为一个快速轻松地创建专业演示文稿的强大工具。

## 功能

- 基于 `slidev-theme-prussianblue` 主题，具有时尚和专业的外观。
- 支持在 Markdown 文件中导入自定义 Vue 组件，提高了灵活性。
- 转换命令可以在 `package.json` 中找到。
- 项目入口文件是 `example.md`。
- 支持 LaTeX，可用于数学表达式。
- 推荐使用另一个主题项目：`slidev-theme-vatis`。

## 快速开始

要开始使用此模板项目，请克隆存储库并运行以下命令以安装依赖项：

```
npm install
```

然后，您可以使用以下命令启动开发服务器：

```
npm run dev
```

这将在 `http://localhost:3030` 启动本地服务器，在那里您可以实时查看和编辑您的演示文稿。

## 转换为 PDF 或 PPT

创建演示文稿后，可以使用以下命令将其转换为 PDF 或 PPT 格式：

```
npm run build
```

这将在 `dist` 目录中生成输出文件。

## 自定义主题

如果您想要自定义主题，请修改 `theme.config.js` 文件，该文件包含 `slidev-theme-prussianblue` 主题的配置选项。

## 结论

使用此模板项目，您可以使用 Slidev 和 `slidev-theme-prussianblue` 主题轻松创建专业演示文稿。它支持自定义 Vue 组件和 LaTeX，提供了广泛的选项，用于创建引人注目和信息丰富的演示文稿。