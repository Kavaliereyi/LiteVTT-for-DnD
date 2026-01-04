# LiteVTT for DnD

A lightweight, single-file Virtual Tabletop (VTT) for D&D and TTRPGs. No server, no installation, just open and play.  

一个轻量级、单文件的 D&D/跑团虚拟桌面工具。无需服务器，无需安装，双击 HTML 文件即可开始。

---

## ✨ Features / 特性

* **⚡ Zero Setup / 零配置** Runs entirely in a browser. Just open the HTML file.  
  完全在浏览器运行，双击 HTML 文件即可开始。

* **🗺️ Map & Grid / 地图与网格** Upload maps with adjustable grid alignment and offset.  
  支持上传地图、对齐网格并微调网格偏移。

* **🌫️ Fog of War / 战争迷雾** Paint and erase fog visibility (Circle/Rect shapes) with real-time transparency control.  
  支持圆形或矩形笔刷绘制/擦除迷雾，具备透明度预览功能。

* **♟️ Token Management / 棋子管理** HP tracking, status effects (with durations), and smooth dragging.  
  支持血量追踪、带回合计时的状态显示以及平滑的拖拽体验。

* **📏 Tools / 工具集** Built-in distance measuring (Shift key) and spell AOE templates.  
  内置 5 尺步进测距工具（按住 Shift）及法术范围模板（圆形/方形）。

* **💾 Save & Load / 存取档** Save your entire campaign state (including multiple scenes) to a local JSON file.  
  支持将整个场景（包括多场景切换）保存为本地 JSON 文件。

---

## 🚀 Quick Start / 快速开始

1. **Download** `Vtt.html` (or clone this repo).  
   **下载** `Vtt.html`（或克隆本项目）。
2. **Open** the file in Chrome, Edge, or Firefox.  
   **打开**：使用主流浏览器直接打开该 HTML 文件。
3. **Upload** an image onto the canvas to load your map.  
   **上传**：拖入或选择一张图片作为战斗地图。
4. **Enjoy** your adventure!  
   **开始**：开启你的冒险之旅！

---

## 🎮 Controls & Usage / 操作指南

### 1. Navigation / 视角控制

| Action / 动作 | Control / 操作 |
| :--- | :--- |
| **Pan Map (平移)** | Middle Mouse Button (Hold) OR Spacebar + Left Click <br> 中键按住拖动 或 空格+左键 |
| **Zoom (缩放)** | Mouse Wheel <br> 鼠标滚轮 |
| **Reset View (重置)** | Click "Reset View" button <br> 点击工具栏“重置视角” |

### 2. Tokens / 角色棋子

* **Add Token / 添加棋子** Use the **"角色"** button to upload token images.  
  点击工具栏“角色”按钮上传图像创建棋子。
* **Move / 移动** Left-click and drag. It will **snap to grid** automatically upon release.  
  左键拖拽平滑移动，松开鼠标后棋子将自动吸附至网格。
* **Context Menu / 右键菜单** **Right-click** a token to set current/max HP and toggle Statuses.  
  **右键点击**棋子可弹出菜单，用于修改 HP 及管理状态。
* **Status Effects / 状态显示** Icons with round-counters will display below the token (supports auto-wrapping).  
  状态图标显示在棋子下方，支持显示剩余回合数及自动换行。

### 3. Combat Tools / 战斗工具

* **📏 Measure / 测距** Hold **Shift** and move mouse. Distance is rounded to 5ft increments (D&D 5e style).  
  按住 **Shift** 键移动鼠标即可测距。距离以 5 尺为单位四舍五入。
* **🔥 Spells / 法术** * **Free Mode**: Place templates anywhere for flexible positioning.  
    **自由模式**：笔刷跟随鼠标，自由放置范围模板。
  * **Grid Mode**: Snaps to the nearest grid center.  
    **网格模式**：模板自动吸附至格点中心。
* **🌫️ Fog of War / 战争迷雾** * **Erase (迷雾模式)**: Removes fog to reveal the map. (擦除迷雾显示地图)  
  * **Add (遮盖模式)**: Restores fog to hide areas. (重新覆盖迷雾)  
  * **Shape (形状)**: Toggle between **Circle** and **Rectangle** brushes. (切换圆/方笔刷)

---

## 🧠 Credits
Developed by **[Kavaliereyi]** with the creative assistance of **Gemini AI**.  
由 **[Kavaliereyi]** 在 **Gemini AI** 的辅助下开发完成。
