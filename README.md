# GWY LaunchPad — 公考工具箱启动器

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.4.1-brightgreen)](https://github.com/kaXianc2-gom/gwy-launchpad/releases)
[![Pages](https://img.shields.io/badge/demo-online-0078D4)](https://kaXianc2-gom.github.io/gwy-launchpad/)

> 8 个工具的入口。设置一次偏好，所有工具自动读取。

单文件 HTML，双击即用。7 张工具卡片，点击打开对应工具。

## 怎么用

1. 把所有工具的 HTML 文件放在同一个文件夹里
2. 双击 gwy-launchpad.html 打开
3. 填写专业/学历/意向省份，保存偏好
4. 点击工具卡片进入

偏好设置存 localStorage，SheetLens、AppTrack 等工具自动读取。

## 工具列表

| 工具 | 作用 |
|------|------|
| TableNorm | 列名标准化 |
| DataVeil | PII 脱敏 |
| SheetLens | 岗位筛选 |
| PostCmp | 岗位对比 |
| AppTrack | 报名追踪 |
| ExamPrep | 行测刷题 |
| PolicySearch | 政策搜索 |

## 数据流

TableNorm → DataVeil → SheetLens → PostCmp → AppTrack（→ ExamPrep / PolicySearch）

## 🌐 在线体验

无需下载，直接使用：**[🔗 在线 Demo](https://kaXianc2-gom.github.io/gwy-launchpad/)**

## 🔐 隐私声明

- **数据不上传**：偏好设置（专业/学历/省份）仅存于浏览器 localStorage
- **无网络请求**：零外部依赖，运行时无任何网络请求
- **无追踪**：不使用任何分析或遥测工具

## 技术

纯 HTML + CSS + JS，无外部依赖。文件约 16KB。

MIT License
