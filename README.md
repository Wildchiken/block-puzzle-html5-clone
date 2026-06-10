# 🧩 Block Puzzle Clone (HTML5)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Tech: Canvas](https://img.shields.io/badge/Tech-HTML5_Canvas-orange.svg)]()
[![Tech: Vanilla_JS](https://img.shields.io/badge/Tech-Vanilla_JS-yellow.svg)]()
[![Size: 48KB](https://img.shields.io/badge/Size-~48KB-brightgreen.svg)]()

基于原生 JavaScript 和 HTML5 Canvas 开发的轻量级方块消除游戏。纯代码驱动，零外部资产依赖，完美适配移动端触屏与桌面端浏览器。

A lightweight, high-performance HTML5 Block Puzzle game built from scratch with Vanilla JS and Canvas. Zero external assets, fully responsive, and optimized for smooth game feel.

🎮 **[在线试玩 / Play Live Demo]([链接](https://wildchiken.github.io/block-puzzle-html5-clone/))**

---

## ✨ 项目亮点 / Core Highlights

没有拼凑感，完全用前端底层 API 还原工业级消除游戏的“爽感（Juiciness）”：

* **🚀 纯代码粒子系统 (Canvas Physics)**: 方块消除时的碎片喷射、渐隐动画以及全清（All Clear）彩蛋，均通过手写重力和阻尼公式在 Canvas 上实时渲染。
* **🎵 实时波形合成音效 (Procedural Audio)**: 摒弃了体积大的 `.mp3` 文件。采用原生 `Web Audio API` 在运行时合成音乐，音调（Pitch）会随着玩家 **Combo 连击数** 动态升高，带来递进式的听觉反馈。
* **📏 像素级碰撞与阴影预览 (Ghost Block)**: 精确的边界盒（Bounding Box）碰撞检测。方块悬停时自动计算矩阵，并渲染半透明的落点预览，优化操作手感。
* **📱 统一下拉交互 (Unified Pointer Events)**: 使用 Pointer Events 完美兼容鼠标与触屏，彻底解决了移动端 Web 游戏长按弹出系统菜单、双击缩放等痛点。
* **⚙️ 数据配置化设计 (Data-Driven)**: 连击夸赞词（如 *GREAT!*, *AMAZING!*）和核心动效数据高度解耦，支持国际化（i18n）一键切换主题文案。

---

## 🚀 运行方法 / Quick Start

单文件架构，无需安装任何构建工具、依赖包或服务器环境。克隆即可游玩：

```bash
# 克隆项目
git clone [https://github.com/yourusername/block-puzzle-html5-clone.git](https://github.com/yourusername/block-puzzle-html5-clone.git)

# 进入目录，双击打开 index.html 即可
cd block-puzzle-html5-clone

```

---

## 🛠️ 技术栈 / Tech Stack

* **Core**: HTML5 / CSS3 / Vanilla JavaScript (ES6+)
* **Graphics**: HTML5 Canvas API (Grid & particle rendering)
* **Audio**: Web Audio API (Procedural sound synthesis)
* **Storage**: `localStorage` (High score and user settings persistence)

---

## 📜 License & Acknowledgements

* **Code**: [MIT License](https://www.google.com/search?q=LICENSE). Feel free to use, modify, and distribute.
* **Inspiration**: This project is an independent open-source clone built strictly for educational, technical practice, and portfolio purposes. Gameplay concepts belong to their respective creators.
*(本项目为开源技术练习，核心玩法与灵感致敬市面流行消除游戏，无任何商业盈利行为。)*
