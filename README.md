# Sally Ren Portfolio

Personal portfolio website for Sally Ren, an AI Product Manager focused on AI product design, evaluation, and user-centered decision tools.

Live site: [sallyren.top](https://sallyren.top)

## Overview

This is a single-page portfolio that presents Sally's background, internship experience, selected product projects, research work, and contact links. The visual system uses an impressionist palette shared with the Offer Decision Tool project: mist blue, lotus pink, cream, and deep blue-gray.

## 迭代记录

这里只记录影响网站结构、核心内容、视觉系统或响应式体验的较大迭代；单句文案、链接或其他小幅调整不单独记录。

- **2026-08-15**：为首页四张个人照片加入本地灯箱预览，支持左右切换、键盘关闭和响应式布局；预览层沿用页面浅色视觉，使用图标控件并避免关闭后留下图片选中描边。
- **2026-08-13**：补充智谱 AI 与 Coreview Capital 两段金融相关实习经历，按时间顺序加入 Experience 时间线并精简描述；同时将首页圆形头像升级为四张个人照片组成的响应式层叠相册，并补齐多尺寸页面的页首与页尾滚动适配。
- **2026-07-29**：完成作品集主体内容与项目展示，加入 OfferDecisionTool 项目卡片，统一印象派视觉系统，并完成移动端布局与滚动分区动效优化。
- **第一版**：搭建个人背景、实习经历、项目、研究成果和联系方式等核心页面结构，并接入 Vercel 部署。

## Tech Stack

- Static HTML
- Tailwind CSS browser build
- Lucide icons
- Font Awesome icons
- Google Fonts: Playfair Display and DM Sans
- Vercel deployment

## Project Structure

```text
.
├── sallyren.html
├── vercel.json
├── assets/
│   ├── profile.jpg
│   ├── offer-decision-tool.png
│   ├── codex-course-project.png
│   ├── markdown-preview-project.png
│   ├── finsearchcomp-paper.png
│   └── xpertbench-paper.png
└── README.md
```

## Local Preview

```bash
python3 -m http.server 5175
```

Then open:

```text
http://127.0.0.1:5175/sallyren.html
```

## Deployment

The site is deployed on Vercel and published at:

[https://sallyren.top](https://sallyren.top)

The repository is connected to GitHub at:

[https://github.com/Arianator-SalD/sally-portfolio](https://github.com/Arianator-SalD/sally-portfolio)
