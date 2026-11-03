# REBIT · 创意摄影作品集

个人创意摄影作品网站，部署于 GitHub Pages，用于视觉中国（VCG）签约供稿人申请展示。

## 在线访问

https://kenneth-g6.github.io/rebit-photography/

## 目录结构

```
├── index.html   # 单文件网站（内联 CSS/JS，无框架）
└── assets/      # 作品图片（当前为示例占位图，待替换为真实作品）
```

## 替换作品照片

1. 将真实作品放入 `assets/`，建议统一为 JPG，文件名如 `work1-silhouette.jpg`；
2. 编辑 `index.html` 中对应 `<img src="assets/...">` 路径、`alt` 文本、卡片标题与分类；
3. 替换 hero 大图为 `assets/hero.jpg`；
4. 移除作品卡片上的「示例占位图」标记与作品区底部提示；
5. 更新「关于」板块的占位文案（简介、设备、所在地、一句话简介、联系邮箱）。

## 本地预览

直接用浏览器打开 `index.html` 即可，无构建依赖。

## 部署

仓库 `main` 分支根目录由 GitHub Pages 自动发布。

## 版权

网站代码与占位示例图仅用于申请展示；替换真实作品后，图片版权归作者本人所有。
