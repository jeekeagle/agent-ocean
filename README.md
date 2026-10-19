# Agent × 海洋 · 课程网站

人工智能和具身智能交叉融合海洋产业发展 · 主讲人 王益国

纯静态课程站点：课程主页 → 课程目录（10 讲）→ 每讲独立的 HTML 课件（键盘翻页 / 概览墙），双击可开、无需构建。

## 结构

```
index.html            课程主页
catalog.html          课程目录（10 讲索引）
lec1-1/ … lec3-2/     势 · 理 · 器 三个模块（8 讲）
lec4/                 用 · 海洋产业智能应用进展（26 页）
lec5/                 用 · Agent 实践应用的基本思路（12 页）
  └── index.html      每讲的聚合外壳（← → 翻页 · O 概览墙 · P 打印）
  └── slides/         每页一个独立 HTML（1920×1080）
  └── *.pdf           各讲 PDF 版课件
```

## 本地预览

```bash
python -m http.server 8000
# 打开 http://localhost:8000
```

也可以直接双击 `index.html`（file:// 协议同样可用）。

## 部署到 Vercel

1. Import this repository → Framework Preset 选 **Other**
2. Build Command 留空，Output Directory 留空（根目录即静态站）
3. Deploy

## 设计约定

- 白底 #FFFFFF · 学术深蓝 #1F4E79 · 中性灰阶，全站 ≤3 色
- 标题 Noto Serif SC 700 · 正文 Noto Sans SC · 数字与英文 JetBrains Mono（Google Fonts）
- 每页 = 短标题 + 一张内联 SVG 证据图；无页码、无水印、无多余标注
- 右上角统一课程标识（神经节点 × 海浪）
