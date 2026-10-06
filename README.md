# Frontend Gallery · 交互式前端设计集

![Bubble Orbit preview](./assets/bubble-orbit-preview.png)

这里收集我的交互式前端实验与游戏化界面设计。每个作品都尽量保持独立，可单独打开，也可以通过总览页浏览。

## 已收录作品

### [Bubble Orbit · 玻璃气泡物理场](./projects/bubble-orbit/)

一个基于 Canvas 2D 的玻璃气泡物理原型：

- 自适应正方形容器
- 慢速漂浮与边缘反弹
- 气泡互撞、自动分离和软形变
- 支持拖拽与松手投掷
- 游戏名长度驱动气泡尺寸
- 背景图保持正向，不跟随碰撞旋转
- 未配置背景图时回退到单色默认填充

## 本地运行

直接打开 `projects/bubble-orbit/index.html` 即可体验当前作品，也可以使用任意静态服务器：

```bash
python -m http.server 8000
```

然后访问 `http://localhost:8000/`。

## 目录结构

```text
frontend-gallery/
├── index.html
├── README.md
├── assets/
│   └── bubble-orbit-preview.png
└── projects/
    └── bubble-orbit/
        └── index.html
```

## 规划

后续前端设计会继续以独立目录加入，并在这里补充预览图、交互说明和访问入口。
