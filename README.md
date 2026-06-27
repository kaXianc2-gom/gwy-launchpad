# 🏛 GWY LaunchPad — 公考工具箱统一启动器

[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Version](https://img.shields.io/badge/version-v1.0.0-green)](https://github.com/kaXianc2-gom/gwy-launchpad/releases)

> 8 个开源公考工具的统一入口。卡片式工具选择器 + 工作流引导 + 全局偏好设置（一次填写，全工具共享）。

## 🧰 工具矩阵

| 工具 | 说明 | 仓库 |
|------|------|------|
| 🧹 TableNorm | 表格列名标准化 | [repo](https://github.com/kaXianc2-gom/table-norm) |
| 🛡 DataVeil | PII 数据脱敏 | [repo](https://github.com/kaXianc2-gom/data-veil) |
| 📊 SheetLens | 岗位筛选评分 | [repo](https://github.com/kaXianc2-gom/sheet-lens) |
| ⚖ PostCmp | 岗位深度对比 | [repo](https://github.com/kaXianc2-gom/post-cmp) |
| 📋 AppTrack | 报名进度追踪 | [repo](https://github.com/kaXianc2-gom/app-track) |
| 📝 ExamPrep | 行测刷题+面试 | [repo](https://github.com/kaXianc2-gom/exam-prep) |
| 🔍 PolicySearch | 政策文件搜索 | [repo](https://github.com/kaXianc2-gom/policy-search) |
| 🏛 LaunchPad | 统一启动器 | 本页面 |

## 🗺 工作流

```
🧹 TableNorm  →  🛡 DataVeil  →  📊 SheetLens  →  ⚖ PostCmp  →  📋 AppTrack
 (清洗数据)       (脱敏隐私)      (筛选评分)       (深度对比)      (追踪进度)
                                                               ↘ 📝 ExamPrep (备考)
                                                               ↘ 🔍 PolicySearch (查政策)
```

## ✨ 功能

- **🃏 工具卡片**：8 张卡片，点击跳转对应 GitHub 仓库
- **🗺 流程引导**：顶部箭头显示推荐使用顺序
- **⚙ 全局偏好**：设置专业/学历/意向省份 → 保存 → 所有工具自动读取
- **🌓 暗色模式**：双击 🏛 图标切换

## 🚀 快速开始

1. [下载 index.html](https://github.com/kaXianc2-gom/gwy-launchpad/releases/latest)
2. 双击打开
3. 填写你的专业/学历/省份 → 点 💾 保存
4. 按工作流顺序使用各工具

## 🔧 技术架构

| 项目 | 说明 |
|------|------|
| 存储 | localStorage 全局偏好 |
| 依赖 | 无（纯 HTML + CSS） |
| 隐私 | 偏好设置本地存储，不上传 |

## 🤖 AI 辅助

本项目使用 Claude（Anthropic Claude Code）辅助开发。

## 📄 许可证

MIT License
