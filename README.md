# 绘纸工坊 · Graph Paper Studio

绘纸工坊是一个可离线使用的纸张生成器。它提供 78 种可打印纸型，包含方格、点阵、六边形、康奈尔笔记、五线谱、分镜、坐标纸和桌游地图。选好纸型后，可以按实际用途设置纸张尺寸、网格间距、线宽、颜色和页边距。

**在线使用** · [简体中文](https://graphpaper.wangruofeng007.com/) · [English](https://graphpaper.wangruofeng007.com/en/)

## 可以用它做什么

| 使用场景 | 纸型与用法 |
| --- | --- |
| 数学作业与工程草图 | 选用方格纸或坐标纸，按题目需要设置网格间距。 |
| 课堂笔记与手帐 | 用康奈尔笔记纸整理提问和摘要，或用浅色点阵纸辅助书写和排版。 |
| 音乐与分镜创作 | 打印五线谱记录旋律，用分镜模板草绘镜头。 |
| 桌游地图 | 选择六边形纸，调整网格大小，再打印地图底稿。 |

如果要反复使用同一套规格，可以收藏「复制链接」生成的网址。需要交给别人直接打印时，分享导出的 PDF 即可。

## 使用方法

1. 在首页搜索或选择纸型，也可以从生成器下方的快速预设开始。
2. 选择 A4、A3、Letter 等规格或输入自定义尺寸。修改参数时，整页与中心细节会同步更新。
3. 下载 PDF 打印，或下载 SVG 用于设计软件、PNG 用于平板笔记。打印时选择「实际大小」或 100%，以保留标定尺寸。
4. 使用「复制链接」分享当前纸型和参数。

## 离线使用

在首页点击「下载应用」，然后用浏览器打开保存的 HTML 文件。也可以直接打开仓库中的 `index.html`（简体中文）或 `en/index.html`（英文）。每个文件包含页面、预览和导出逻辑，无需安装依赖。

如果要在本地通过 HTTP 预览，在仓库根目录运行：

```sh
python3 -m http.server 8000
```

然后打开 [简体中文](http://localhost:8000/) 或 [English](http://localhost:8000/en/)。

## 部署与来源

Cloudflare Pages 从 `main` 分支自动部署，静态输出目录为仓库根目录，无需构建命令。

项目基于 Kevin MacLeod 的 [Incompetech Graph Paper 2.3](https://incompetech.com/graphpaper/) 改编。本应用及生成的 PDF 采用 [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)。

---

Graph Paper Studio generates 78 printable paper types in your browser. Customize dimensions, spacing, line weight, colors, and margins, then export PDF, SVG, or PNG. Open the [English edition](https://graphpaper.wangruofeng007.com/en/) or download it as a standalone HTML app for offline use.
