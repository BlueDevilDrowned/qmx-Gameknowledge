# 游戏知识库

这是一个由工作室共同维护的游戏知识库，记录游戏设计、开发、工具、运营和项目复盘经验。

网站地址：<https://bluedevildrowned.github.io/qmx-Gameknowledge/>

## 本地运行

需要 Python 3.10 或更高版本：

```bash
python -m venv .venv
# Windows
.venv\\Scripts\\activate
# macOS / Linux
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

打开 <http://127.0.0.1:8000> 预览网站。

## 写作方式

- 知识库页面放在 `docs/` 下，并在 `mkdocs.yml` 的 `nav` 中登记。
- 博客文章放在 `docs/blog/posts/` 下，文件名使用有意义的英文短名。
- 文章使用 Markdown 编写，提交后由 GitHub Actions 自动构建和发布。
- 新增文章前请阅读 [贡献指南](CONTRIBUTING.md)。

## 发布流程

向 `main` 分支提交代码后，GitHub Actions 会自动构建并部署到 GitHub Pages。

