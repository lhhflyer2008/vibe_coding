# AI×教学 —— 面向教师的 AI 赋能系列课程网站

**从智能体到教学网站：AI 辅助教学构建实战三部曲**

一个纯静态的中文教学网站，为中学教师提供四讲 AI 赋能教学系列课程的在线学习平台。

## 课程内容

| 讲次 | 主题 | 核心内容 |
|------|------|---------|
| 第一讲 | 教学网站自己做 | AI 工具认知、Vibe Coding、Trae IDE 入门、《春》PBL 实战 + 七大学科扩展 |
| 第二讲 | AI 创造工作坊 | MCP 协议与搭建、Git 代码托管、Skill 机制、六大学科示例 |
| 第三讲 | 晚修答疑与路演 | 网站完善、学生作品路演、答疑讨论 |
| 第四讲 | 人人都是智能体创作者 | Coze 平台入门、作文批改助手搭建（完整四步流程） |

## 项目结构

```
Vibe Coding/
├── index.html          # 课程首页（Hero + 四讲概览卡片）
├── lecture1.html       # 第一讲：教学网站自己做（816行，含七学科PBL案例）
├── lecture2.html       # 第二讲：AI创造工作坊（MCP + Skill + Git）
├── lecture3.html       # 第三讲：晚修答疑与路演
├── lecture4.html       # 第四讲：Coze智能体创作（含作文批改系统完整搭建）
├── css/
│   └── styles.css      # 共享样式表（Editorial Scholarly 设计系统）
└── README.md
```

## 技术栈

- 纯 HTML/CSS/JS，零外部依赖
- 系统中文字体栈（无需加载 Google Fonts，国内网络环境无需翻墙）
- 响应式设计（桌面 / 平板 / 手机三端适配）
- CSS 自定义属性驱动的设计系统

## 设计系统

基于 UI/UX Pro Max 的 **Editorial Scholarly** 风格：

- **配色**：暖象牙白底色 + 学术青绿主色 + 赤陶色强调
- **字体**：系统中文字体栈 — Songti SC / PingFang SC / Microsoft YaHei
- **间距**：8dp 节奏系统
- **图标**：CSS 伪元素 + SVG mask-image 装饰系统

## 使用方式

直接在浏览器中打开 `index.html` 即可浏览全部内容。无需构建工具、无需服务器。

部署到生产环境时，将整个目录上传至任意静态托管服务（GitHub Pages、Cloudflare Pages、腾讯云静态托管等）。

## 许可

本课程内容仅供教学使用。