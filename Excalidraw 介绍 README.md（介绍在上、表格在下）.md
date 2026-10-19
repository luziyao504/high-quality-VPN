# Excalidraw — 开发者必备的开源手绘风白板

> 一个免费、开源、无需注册的在线绘图工具，画出的图自带"手绘画风"，写文档、讲架构、画流程图都极香。

[![GitHub stars](https://img.shields.io/github/stars/excalidraw/excalidraw?style=flat-square&logo=github)](https://github.com/excalidraw/excalidraw)
[![GitHub license](https://img.shields.io/github/license/excalidraw/excalidraw?style=flat-square)](https://github.com/excalidraw/excalidraw/blob/master/LICENSE)
[![Website](https://img.shields.io/badge/website-excalidraw.com-blue?style=flat-square)](https://excalidraw.com)

---

## 📌 它是干什么的

**Excalidraw** 是一个跑在浏览器里的白板应用。你打开 [excalidraw.com](https://excalidraw.com) 就能直接画矩形、箭头、文字，它会自动把这些图形渲染成"手绘风"——看起来像在纸上随手画的，但又整齐到可以直接贴进技术文档、README、PPT 里。

它最爽的地方是**零门槛**：不用装软件、不用注册账号、不用付费。打开网址就是画布，按 `R` 画矩形、按 `O` 画圆、按 `P` 自由涂鸦，鼠标都可以收起来。画完一键导出 PNG 或 SVG，贴到 GitHub、Notion、飞书文档里都好看。

而且它是**完全开源**的项目，代码都在 GitHub 上（[github.com/excalidraw/excalidraw](https://github.com/excalidraw/excalidraw)），可以自己 Docker 部署一份，数据全在自己服务器上，不怕哪天网站跑路。

## 🎯 什么时候会用到它

写技术文档需要配一张架构图的时候；面试或者给同事讲方案需要边讲边画白板的时候；脑暴产品思路需要一张自由布局的思维导图的时候；画数据库 ER 图、业务流程图、系统时序图的时候；做教学答疑需要一张让学生不紧张的示意图的时候——这些场景 Excalidraw 都比 PPT、Visio、Draw.io 顺手。

手绘风还有个隐藏好处：它画出来的图"不那么正式"，读者看到会觉得亲切，不会像看工程图纸那样有压力。所以很多开发者喜欢把它画的图直接放进开源项目 README，整个项目瞬间就有温度了。

---

## 📊 速览表

| 项目 | 说明 |
|---|---|
| 🌐 官网地址 | [https://excalidraw.com](https://excalidraw.com) |
| 🐙 GitHub 仓库 | [github.com/excalidraw/excalidraw](https://github.com/excalidraw/excalidraw) |
| 💰 价格 | 完全免费 |
| 📜 开源协议 | MIT（随便用、随便改、随便二开） |
| 🎨 画风 | 手绘风自动渲染，歪歪扭扭但整齐 |
| ⌨️ 操作方式 | 键盘快捷键为主（R/O/P/箭头） |
| 🤝 协作 | 生成链接即可多人实时同画 |
| 📦 内置组件 | 流程图图形、云和数据库图标、UX 组件库 |
| 💾 数据存储 | 自动存浏览器本地，断网也能画 |
| 📤 导出格式 | PNG / SVG / JSON（可二次编辑） |
| 🐳 自部署 | 官方 Docker 镜像，一行命令起服务 |
| 🔌 生态 | VS Code 插件、嵌入 Notion / Obsidian |
| ✅ 优点 | 免费开源、画风独特、零门槛、可自部署 |
| ⚠️ 局限 | 复杂严格 UML 图不够用、中文渲染偶尔糊 |
| 🎯 典型用途 | 架构图、流程图、脑暴、ER 图、白板讲解 |

---

## 🏁 30 秒上手

1. 打开 [excalidraw.com](https://excalidraw.com)
2. 按 `R` 拖一个矩形出来
3. 按 `→` 拖一根箭头连到另一个矩形
4. 双击文字改成"用户"、"服务器"、"数据库"
5. 左上角 `Export` → 选 `SVG` → 保存

想自己部署：

```bash
docker run -d -p 8080:80 excalidraw/excalidraw
```

访问 `http://localhost:8080` 就是你自己的 Excalidraw。

---

<p align="center">
如果觉得好用，记得去 GitHub 给原作者点个 ⭐️<br>
<a href="https://github.com/excalidraw/excalidraw"><b>excalidraw/excalidraw</b></a>
</p>
