# 给爸爸的一颗生日星球 🎂

为爸爸准备的单文件互动生日礼物。当前版本：Three.js 手势版。

## 内容

- 散乱粒子自动聚合成紫色、冰银色星球和双层星环。
- 变形成猫山王榴莲蛋糕，插有六根蜡烛。
- 最后聚合成女儿送给爸爸的祝福。
- 可选 MediaPipe 摄像头手势：手掌转动控制旋转；张手靠近放大、握拳远离缩小。
- 支持触屏拖动、双指缩放和配乐开关。

## 打开方式

用现代浏览器打开 `index.html`，或通过 GitHub Pages 发布。Three.js 已内嵌，不需要 npm 安装或构建。手势模型首次使用需要联网，并须由用户授权摄像头；不启用手势也能游玩。

## GitHub Pages

仓库 Settings → Pages → Deploy from a branch，选择 main 分支和 /(root)。

## 浏览器限制

摄像头需安全上下文（HTTPS 或 localhost），并依赖浏览器支持。浏览器可能限制自动声音播放。WebGL 不可用时自动使用 Canvas 兼容渲染。

## 第三方许可

Three.js © 2010–2024 Three.js Authors，MIT 许可，原始许可头保留在内嵌模块中。MediaPipe 通过 Google 官方模型与 jsDelivr 加载。
