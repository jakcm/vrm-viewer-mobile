# VRM 模型查看器

基于 [Three.js](https://threejs.org/) + [@pixiv/three-vrm](https://github.com/pixiv/three-vrm) 的 VRM 模型查看器，支持 VRMA 动画播放。

## 功能

- 🎭 **模型选择** — 内置示例模型 + 多个自定义 VRM 模型，支持导入本地文件
- 🎬 **动画播放** — 11 种 VRMA 动画动作（生气、害羞、拍手、跳跃等）
- 📱 **移动端适配** — 响应式布局，触摸手势操作（旋转、缩放、平移）
- 🇨🇳 **中文界面** — 全中文 UI
- 🎨 **工具收起** — 控制面板默认收起，不遮挡 3D 主画面
- 🌐 **纯前端** — 无需后端，静态部署到 GitHub Pages

## 使用方法

1. 打开页面，自动加载示例模型
2. 点击右上角菜单按钮展开控制面板
3. 在「模型选择」下拉框中选择不同模型，或导入本地 VRM 文件
4. 在「动画动作」中选择动画
5. 使用「播放控制」播放、暂停、停止动画
6. 在 3D 画面上拖拽旋转模型，双指缩放

## 技术栈

- Three.js r176
- @pixiv/three-vrm v3
- @pixiv/three-vrm-animation v3
- 纯 HTML/CSS/JS，无构建依赖

## 部署

部署到 GitHub Pages：

```bash
git push origin main
# GitHub Pages 自动部署
```

## 来源

基于 [tk256ailab/vrm-viewer](https://github.com/tk256ailab/vrm-viewer) 改造。

## License

MIT
