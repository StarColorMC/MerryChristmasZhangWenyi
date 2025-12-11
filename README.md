# 🎄 Merry Christmas, Zhang Wenyi! 🎄

一个精美的圣诞主题3D互动网页项目，使用Three.js构建，包含手势识别、摄像头互动等丰富功能。

## ✨ 功能特性

- 🎨 **3D圣诞树渲染** - 使用Three.js构建的豪华3D圣诞树场景
- 🎭 **多种显示模式** - 支持树形模式、散射模式、焦点模式
- 👋 **手势识别** - 基于MediaPipe的手势识别互动功能
- 📷 **摄像头互动** - 实时摄像头画面与3D场景结合
- 🎵 **音乐播放** - 支持背景音乐播放
- 📊 **访问统计** - 集成不蒜子访问统计
- 📱 **响应式设计** - 适配桌面端和移动端

## 🚀 快速开始

### 本地运行

1. 克隆或下载项目到本地
2. 使用任意HTTP服务器打开项目（推荐使用VS Code的Live Server插件）
3. 在浏览器中访问 `index.html`

### 部署到Vercel

项目已配置 `vercel.json`，可以直接部署到Vercel：

```bash
# 安装Vercel CLI（如果还没有）
npm i -g vercel

# 在项目目录下运行
vercel
```

或者直接在 [Vercel官网](https://vercel.com) 导入GitHub仓库进行部署。

## 📁 项目结构

```
.
├── index.html              # 主页面文件
├── Miss.ZhangWenYi.html    # 其他页面
├── test.html               # 测试页面
├── vercel.json             # Vercel部署配置
├── baby/                   # 图片资源文件夹
│   └── *.jpg, *.png        # 图片文件
└── music/                  # 音乐资源文件夹
```

## 🛠️ 技术栈

- **Three.js** - 3D图形渲染
- **MediaPipe** - 手势识别
- **Font Awesome** - 图标库
- **不蒜子** - 访问统计

## 📝 注意事项

1. **MediaPipe模型加载**：手势识别功能需要加载MediaPipe模型，如果在中国大陆可能需要VPN或下载模型到本地
2. **HTTPS要求**：摄像头功能需要在HTTPS环境下运行
3. **浏览器兼容性**：建议使用Chrome、Edge等现代浏览器

## 📄 许可证

本项目仅供个人使用。

## 💝 致谢

特别为张文译准备的圣诞礼物项目。

---

**Merry Christmas! 🎅🎄✨**

