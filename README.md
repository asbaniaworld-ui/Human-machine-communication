# 人机传播 · 「兔了个」文案助手

深圳大学「人机传播」课程汇报用 **横向翻页 HTML PPT**（13 页），单文件驱动 + 本地素材。

## 预览

在项目目录启动本地服务器后访问 `index.html`：

```bash
python -m http.server 8777
```

浏览器打开：<http://127.0.0.1:8777/index.html>

**翻页**：`→` / `↓` / `空格` 下一页 · `←` / `↑` 上一页 · 底部圆点跳转

## 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 主文件（样式、页面、ECharts、动效脚本） |
| `f489eac3bdfc1890095f84709a6caaf2.mp4` | 第 3 页 GPT 演示视频 |
| `persona-01.png` ~ `persona-04.png` | 第 6 页用户画像卡片（点击图表切换） |
| `logo-mascot.png` / `logo-badge.png` | 品牌素材 |
| `orb-glow.png` | 可选光效素材 |
| `人机传播.pdf` | 原始文案 / 参考 PDF |

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
