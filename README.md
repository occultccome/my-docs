# 我的 MkDocs 技术文档

## 项目简介
本项目是“通过 GitHub Actions 自动部署静态文档到 GitHub Pages”的个人实践项目。
使用 Markdown 和 MkDocs Material 搭建，实现了“推送文档 -> 自动构建 -> 自动部署 -> 网页更新”的自动化流程。

## 核心链接
- **最终网站地址**：[https://occultccome.github.io/my-docs/](https://occultccome.github.io/my-docs/)
- **个人实验报告**：[点击查看个人实验报告](report/README.md)

## 本地预览命令
如果你在本地克隆了本项目，可以通过以下命令进行本地预览：

```bash
# 1. 安装依赖（建议在虚拟环境中）
python -m pip install -r requirements.txt

# 2. 启动本地预览服务器
python -m mkdocs serve