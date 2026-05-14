# 故宫博物院静态导览站

一个纯静态多页练习项目，包含首页以及 4 个独立内容页：

- `index.html`：导览首页
- `about.html`：博物院简介
- `axis.html`：中轴亮点
- `visit.html`：参观信息
- `route.html`：推荐路线

## 项目结构

```text
.
├─ assets/
│  ├─ images/
│  │  └─ forbidden-city-meridian-gate.jpg
│  └─ styles/
│     ├─ base.css
│     ├─ components.css
│     ├─ main.css
│     └─ pages.css
├─ index.html
├─ about.html
├─ axis.html
├─ visit.html
└─ route.html
```

## 本地预览

如果已经启动了静态服务器，可直接访问：

- `http://127.0.0.1:8000/index.html`

如果需要重新启动一个本地预览服务，可在项目根目录执行：

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

## 维护约定

- 所有 HTML、CSS、Markdown 文件统一使用 UTF-8 编码。
- 页面继续保持纯静态结构，不引入框架。
- 公共视觉资源优先放在 `assets/` 目录中，减少外链依赖。
