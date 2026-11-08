# REBIT · 创意摄影作品集

个人创意摄影作品网站，部署于 GitHub Pages，用于视觉中国（VCG）签约供稿人申请展示。

## 在线访问

https://kenneth-g6.github.io/rebit-photography/

## 目录结构

```
├── index.html   # 单文件网站（内联 CSS/JS，无框架）
└── assets/      # 19 张网页尺寸图（hero ×1 + 作品 ×18，50-347KB）
```

## 作品与设备

- 摄影设备：FUJIFILM X-M5
- 作品网格采用 CSS columns 瀑布流，保留原图构图比例（4:3 / 3:2 / 2:3 混排），不强制裁切
- 当前收录源目录全部 18 张：红叶午后、玄凤、双鸟、并栖、对望、窗边橘影、港口背影、暮光飞鸟、海风、群鸥、海平线、远舟、栏杆旁、庭院白衫、竹间石兽、砖墙与白裙、庭园台阶、仰视

## 替换 / 新增作品

1. 新图放入 `assets/`，长边建议 1400-1600px、JPEG（quality 80 左右），hero 可用 2000px；
2. 在 `index.html` 的 `.works-grid` 内按现有 `<figure class="work-card reveal">` 模版新增卡片，填写 `src` / `alt` / `data-name` / `data-tag` / 卡片标题与分类；
3. 替换 hero 图：`assets/hero.jpg`；
4. 同步「关于」板块信息（设备、所在地、一句话简介、联系邮箱）。

## 本地预览

直接用浏览器打开 `index.html` 即可，无构建依赖。

## 部署

仓库 `main` 分支根目录由 GitHub Pages 自动发布；推送后约 1 分钟内更新。

## 版权

站内全部摄影作品版权归作者 REBIT 所有，未经授权请勿转载或商用。含人物的作品在用于签约供稿前需确认肖像权授权。
