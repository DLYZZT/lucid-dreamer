# Lucid Dreamer | Gesture-Controlled Particle System

一个基于 Three.js 和 MediaPipe Hands 的交互式粒子系统，通过手势控制粒子的形态和扩散效果。

An interactive particle system built with Three.js and MediaPipe Hands, allowing you to control particle shapes and dispersion effects through hand gestures.

![Demo](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

**🌐 Live Demo: [heart.dlyzzt.top](https://heart.dlyzzt.top)**

## 🎬 演示视频 | Demo Video

https://github.com/user-attachments/assets/demo.mov

> 通过手势控制粒子的形态变化 | Control particle shapes through hand gestures

## ✨ 特性 | Features

- 🎨 **多种粒子形态** - 破碎之心、土星光环、莲花、烟花爆炸、基础球体
- 🖐️ **实时手势识别** - 使用 MediaPipe Hands 进行精准的手势追踪
- 📱 **移动端优化** - 完全支持 iOS 和 Android 设备
- 🎯 **双手/单手控制** - 支持双手距离控制和单手捏合控制
- 🌈 **自定义颜色** - 实时调整粒子颜色
- 🔮 **自动演示模式** - 未检测到手势时自动呈现呼吸效果
- 💫 **流畅动画** - 基于 WebGL 的高性能渲染

## 🎮 交互方式 | Controls

### 双手模式 | Two-Hand Mode
- 将双手伸入摄像头视野
- 两手距离**近** → 粒子聚合成完整形态
- 两手距离**远** → 粒子扩散炸开

### 单手模式 | One-Hand Mode
- 使用食指和拇指
- 捏合 (👌) → 粒子聚合
- 张开 (✋) → 粒子扩散

### UI 控制 | UI Controls
- ⚙️ **设置按钮** - 显示/隐藏控制面板
- 🎨 **颜色选择器** - 自定义粒子颜色
- 🔄 **模型选择** - 切换不同的粒子形态
- ⛶ **全屏按钮** - 进入全屏体验

## 🚀 快速开始 | Quick Start

### 🌐 在线体验 | Live Demo

**[✨ 立即体验 / Try Now →](https://heart.dlyzzt.top)**

直接访问已部署的在线版本，无需任何配置！

---

### 本地运行 | Local Development

```bash
# 克隆仓库
git clone https://github.com/DLYZZT/lucid-dreamer.git
cd lucid-dreamer

# 使用简单的 HTTP 服务器
# Python 3
python -m http.server 8000
```

## 🤝 贡献 | Contributing

欢迎提交 Issue 和 Pull Request！

Contributions are welcome! Feel free to submit issues and pull requests.

## 📄 许可证 | License

MIT License - 详见 [LICENSE](LICENSE) 文件

## 🙏 致谢 | Acknowledgments

- [Three.js](https://threejs.org/) - 强大的 3D 图形库
- [MediaPipe](https://google.github.io/mediapipe/) - Google 的机器学习解决方案
- 灵感来源于各种粒子系统和交互艺术作品

## 📞 联系方式 | Contact

- 项目链接: [https://github.com/DLYZZT/lucid-dreamer](https://github.com/DLYZZT/lucid-dreamer)

---

⭐ 如果这个项目对你有帮助，请给个 Star！

⭐ If you find this project helpful, please give it a star!
