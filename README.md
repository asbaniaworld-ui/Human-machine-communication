# 人机传播 · 「兔了个」文案助手

深圳大学「人机传播」课程汇报用 **横向翻页 HTML PPT**（13 页），单文件驱动 + 本地素材。

小组：黄之颖（2024080126）· 洪小喻（2024080093）

## 离线交付包（推荐发给别人）

下载仓库中的 **`Final_Project.zip`**，解压后：

1. 双击 **`start.bat`**（需已安装 Python）
2. 浏览器约 1 秒后自动打开 PPT  
   若未自动打开：<http://127.0.0.1:8777/index.html>
3. 也可阅读包内 **`使用说明.txt`**

包内含：HTML PPT、视频、用户画像图、品牌素材、课程 PDF、项目说明 PDF、提交用 PowerPoint。

## 在本仓库预览

```bash
python -m http.server 8777
```

浏览器打开：<http://127.0.0.1:8777/index.html>

**翻页**：`→` / `↓` / `空格` 下一页 · `←` / `↑` 上一页 · 底部圆点跳转

## 仓库文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | HTML 主 PPT（样式 / 动效 / ECharts） |
| `Final_Project.zip` | 完整离线交付压缩包 |
| `f489eac3….mp4` | 第 3 页 GPT 演示视频 |
| `persona-01.png` ~ `persona-04.png` | 第 6 页用户画像卡片 |
| `logo-mascot.png` / `logo-badge.png` / `logo-character.png` | 品牌 LOGO 素材 |
| `orb-glow.png` | 可选光效素材 |
| `人机传播.pdf` | 课程参考 PDF |
| `让人与AI的表达连接.pdf` | 项目说明 PDF |
| `2024080126 黄之颖 2024080093 洪小喻.pptx` | 提交用 PowerPoint 版 |

## 页面概览

1. 封面（打字机 · 粉蓝配色）
2. 初心 · AI 还不能做到什么
3. GPT 视频
4. 核心洞察
5. 定位 · 三步方案
6. 问卷数据总览（可点击切换用户画像）
7. 调研结论（卡片点击打字）
8. 竞品分析（三卡从左弹出）
9. 开发价值
10. 开发过程
11. Demo
12. 不足
13. 收尾

## 技术栈

- 纯 HTML / CSS / JavaScript
- [ECharts 5](https://echarts.apache.org/)（CDN）
- Noto Sans SC

## 许可

课程作业用途，素材请勿商用。
