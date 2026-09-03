# SHI HAN Portfolio

一个不依赖框架的静态多页作品集。首版重点是信息层级和作品展示，后续可直接替换真实素材与链接。

## 本地预览

在 `portfolio` 目录运行任一静态服务器，例如：

```powershell
python -m http.server 4173
```

访问 `http://localhost:4173/`。

## 发布前需要替换

1. 元素回廊和弈者已使用正式展示截图；后续可以直接用同名文件替换为更新版本，或补充 GIF。
2. 两个游戏的 Live Demo 已填写。继续全局搜索 `LINK TO ADD`、`URL TO ADD`、`TO UPDATE` 和 `controller-package`，补全 GitHub、文档、Controller、邮箱与包名。
3. 根据最终事实校对项目文案，尤其是工具命令与公开能力。

## GitHub Pages

最简单的方式是把 `portfolio/` 作为站点发布目录。若仓库还包含其他工程，可使用 GitHub Actions 上传该目录；确认仓库名和目标 URL 后再添加工作流，避免路径前缀配置错误。
