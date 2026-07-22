# 明日方舟：瘦金体战术与欧洲手稿典藏册 (Arknights Atelier Zero)

<p align="center">
  <img src="assets/amiya.png" alt="Arknights Atelier" width="180" />
</p>

<p align="center">
  <strong>融合东方瘦金体书法艺术与欧洲中世纪手抄本典藏风格的《明日方舟》沉浸式战术 Landing Page</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Font-瘦金体%2FEuropean%20Script-cfa052?style=for-the-badge" alt="Typography" />
</p>

---

## 📖 项目简介 (Overview)

**Arknights Atelier Zero** 是一款为《明日方舟》(Arknights) 玩家与视觉艺术爱好者打造的精美战术主题展示主页。

项目打破常规科技感 UI 模版，巧妙地将**中国传统书法名作【瘦金体】**的筋骨笔锋，与**欧洲中世纪羊皮纸手抄本 (Illuminated Manuscript)** 的金箔花体首字、罗马衬线字体融合。配以罗德岛战术红与暖石羊皮纸底色，呈现独特而优雅的典藏美学。

---

## ✨ 核心特色 (Key Features)

- 🖋️ **双重中西字体审美体系**
  - **东方瘦金体**：内置定制瘦金体字体文件 (`assets/shoujinti.ttf`)，彰显骨力遒劲、瘦硬通神的东方书法意境。
  - **欧洲手抄本花体**：采用 *Cinzel Decorative*、*Pinyon Script*、*Playfair Display* 等古典字体与首字花体框 (Illuminated Drop Cap)。

- 🛡️ **罗德岛干员战术图鉴 (Operators Archive)**
  - 精心收录阿米娅 (Amiya)、凯尔希 (Kal'tsit)、银灰 (SilverAsh)、陈 (Chen)、德克萨斯 (Texas)、维什戴尔 (Wisadel)、浊心斯卡蒂 (Skadi)、艾雅法拉 (Eyjafjalla) 等罗德岛核心干员。

- ⚔️ **8大职业全景阵列 (Classes Visuals)**
  - 完整呈现先锋 (Vanguard)、近卫 (Guard)、重装 (Defender)、狙击 (Sniper)、术师 (Caster)、医疗 (Medic)、辅助 (Supporter)、特种 (Specialist) 职业图徽。

- 🌌 **源石微粒与羊皮纸质感 (Originium Particle Canvas)**
  - 原生 HTML5 Canvas 绘制动态源石浮游微粒，叠加羊皮纸点状纹理，配合浮动渐变效果。

- ⚡ **零依赖与极速加载 (Zero Dependencies)**
  - 纯原生 HTML5 + CSS3 (CSS Variables) + Vanilla JS 开发，无需依赖 Node.js 打包构建，开箱即用。

---

## 📁 目录结构 (Directory Structure)

```text
arknights-atelier-landing-v17c/
├── index.html              # 核心主页面 HTML 与 CSS/JS 架构
├── README.md               # 项目详细说明文档
└── assets/                 # 静态资源目录
    ├── shoujinti.ttf       # 瘦金体中文字体文件
    ├── amiya.png           # 干员及主视觉图像资源
    ├── chen.png
    ├── eyjafjalla.png
    ├── kalts.png
    ├── ling.png
    ├── mlynar.png
    ├── silverash.png
    ├── skadi.png
    ├── surtr.png
    ├── texas.png
    ├── w.png
    ├── battles/            # 战术关卡与战场实况截图
    ├── classes/            # 8大干员职业图标
    └── operators/          # 英雄卡片高精人物立绘
```

---

## 🚀 快速开始 (Quick Start)

### 方式一：直接双击打开
由于本工程为纯原生前端结构，直接在本地双击 `index.html` 或通过任意浏览器（Chrome / Edge / Firefox / Safari）打开即可体验。

### 方式二：使用本地静态 HTTP 服务器
若使用 VS Code 等编辑器，推荐开启本地服务器以获得最佳在线字体与静态资源加载效果：

```bash
# 使用 Python 启动本地服务器
python -m http.server 8000

# 或使用 Node.js npx serve
npx serve .
```

打开浏览器访问 `http://localhost:8000` 即可预览。

---

## 🛠️ 技术栈 (Tech Stack)

| 模块 | 技术方案 |
| :--- | :--- |
| **结构与标记** | HTML5 (Semantic Tags) |
| **样式与布局** | CSS3 (Flexbox / CSS Grid / CSS Custom Properties) |
| **特效与交互** | Vanilla JavaScript (Canvas API / Intersection Observer) |
| **字体呈现** | Shoujinti Font (`.ttf`) + Google Fonts API |

---

<p align="center">
  <i>ARKNIGHTS © HYPERGRYPH / RHODES ISLAND TACTICAL ATELIER</i>
</p>
