# MkDocs 自动部署实验

站点：[GitHub Actions 实验文档](https://iamai-dev.github.io/my-docs/)。

```sh
python -m pip install -r requirements.txt
python -m mkdocs build --strict
```

仓库的 Pages 来源设为 GitHub Actions。工作流在 `main` 的文档、配置或依赖变更时构建站点，将生成的文件保存在 `gh-pages`，同时上传同一份构建产物供 GitHub Pages 的部署任务使用。
