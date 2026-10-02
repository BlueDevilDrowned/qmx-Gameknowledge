# 贡献指南

## 新增知识库页面

1. 在 `docs/` 下选择合适的目录创建 Markdown 文件。
2. 更新 `mkdocs.yml` 中的 `nav`，让页面出现在导航中。
3. 使用清晰的标题、步骤和代码示例，并注明适用版本。

## 新增博客文章

在 `docs/blog/posts/` 中创建 Markdown 文件，并加入文章元数据：

```yaml
---
date: 2026-10-02
authors: [studio]
categories:
  - 游戏开发
tags:
  - 示例
---
```

## 提交规范

提交信息建议使用以下前缀：

- `docs:` 新增或修改知识内容
- `fix:` 修正错误
- `style:` 调整网站样式
- `chore:` 修改构建或工作流

提交前请在本地执行 `mkdocs build --strict`，确保网站可以正常构建。

