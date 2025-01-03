# 前端学习演示平台

这是我的前端学习记录平台，用于实践和展示各种前端技术。每个演示都是学习过程中的实践成果。

## 学习项目演示

### 1. 音频可视化 (audio.html)

学习 Web Audio API 时的实践项目，实现了音频可视化效果。

**学习要点：**

- Web Audio API 的基本使用
- Canvas 动画绘制
- 音频数据实时处理
- CSS 动效设计

**实现效果：**

- 实时音频波形展示
- 动态渐变色效果
- 呼吸动画背景
- 光晕动画效果

### 2. Grid 布局动画 (grid-animation.html)

学习现代 CSS Grid 布局和动画效果时的练习项目。

**学习要点：**

- CSS Grid 布局系统
- CSS 新特性 :has() 选择器
- CSS 动画和过渡效果
- 网格布局动态变化

**实现效果：**

- 九宫格网格布局
- 鼠标悬停时格子动态扩展为 2x2 大小
- 平滑的过渡动画
- 渐入式加载动画

## 技术要点总结

### 已实现的技术

- HTML5
  - 语义化标签
  - Canvas 绘图
  - Audio 音频处理
- CSS3 现代特性
  - Grid Layout 网格布局
  - Animation 动画系统
  - Transform 变换效果
  - 现代选择器 (:has)
- JavaScript
  - Web Audio API
  - Canvas API
  - requestAnimationFrame 动画

## 本地运行指南

1. 克隆项目
   bash
   git clone [your-repository-url]

2. 使用本地服务器运行
   bash

   使用 Python 启动简单服务器
   python -m http.server

   或使用 Node.js 的 http-server
   npx http-server

3. 访问项目
打开浏览器访问 `http://localhost:8000`

## 项目结构

```
├── index.html          # 演示项目导航页
├── audio.html         # 音频可视化练习
├── grid-animation.html # Grid布局动画练习
└── README.md          # 项目文档
```

## 浏览器兼容性

主要在以下现代浏览器中测试：
- Chrome (推荐)
- Firefox
- Safari
- Edge

**注意：** :has 选择器需要现代浏览器支持

## 参考资源

- MDN Web Docs
- CSS-Tricks
- Web.dev

## 未来计划

- [ ] 添加更多交互效果示例
- [ ] 实现3D动画效果
- [ ] 添加更多音频可视化效果
- [ ] 优化移动端适配
