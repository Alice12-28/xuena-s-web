# ⚖️ 中国法律助手 · Legal Intelligence Daily

一站式中国法律资讯智能平台，涵盖**法律法规查询、每日立法更新、热门案件判决追踪、专业律师讨论区**四大核心功能，并支持一键生成图文并茂的每日法治报告并导出 PDF。

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-38bdf8?logo=tailwindcss)
![Status](https://img.shields.io/badge/Status-Production-success)

---

## ✨ 核心功能

### 📜 1. 中国法律法规查询
- **多维检索**：支持关键词搜索、效力级别筛选（法律/行政法规/部门规章/司法解释/地方性法规）、法律部门筛选（民商法/刑法/行政法/经济法/社会法/程序法/宪法）
- **七大法律部门**：快速入口分类导航，宪法、民商法、刑法、行政法、经济法、社会法、程序法一键直达
- **热门检索词**：民法典、个人信息保护法、刑法修正案、反垄断法、劳动合同法、知识产权等高频词条快速检索
- **结构化呈现**：包含发布机关、发布日期、施行日期、条款数量、生效状态、内容摘要等完整信息，重点法规高亮标注

### 🆕 2. 每日法律法规更新
- **实时追踪**：覆盖全国人大、国务院、最高法、最高检、各部委最新立法、修法、司法解释动态
- **分类筛选**：新发布 / 修订 / 征求意见 / 司法解释四类快捷标签
- **状态标识**：每一项标注发布机关、生效状态、重要程度标签（重要/典型案例/民生关注/绿色法治/刑事指导等）

### ⚖️ 3. 每日热门案件判决
- **全网监测**：汇总全网关注的重大案件、典型判例、指导案例
- **类型划分**：刑事、民事、商事/经济、行政、知识产权五大类型分类浏览
- **深度展示**：含审理法院、法院级别、判决结果、案情摘要、裁判要点
- **裁判要点卡片**：黄色高亮卡片提炼案件关键法律适用问题与典型意义
- **热度排序**：基于全网关注度与法律典型性双维度评分

### 💬 4. 律师讨论区
- **热门话题榜**：Top 3 热点法律话题，展示讨论热度、回复数、浏览量
- **专业观点汇总**：汇聚知名律所合伙人、资深律师、法学院教授对热点法律问题的专业解读
- **认证标识**：区分认证专家与普通律师观点
- **立场标签**：明确标注观点倾向（严格适用/合规建议/支持保护/实务指引等）
- **互动功能**：点赞、回复、分享、收藏

### 📑 5. 每日法治报告与 PDF 导出
- **一键生成**：自动整合当日立法动态、热点判例、律师观点为结构化报告
- **图文并茂**：封面页、执行摘要页（含 KPI + CSS 条形图）、立法更新页、判例页、观点页、方法说明页共 **6 页 A4 版式**
- **浏览器端 PDF 导出**：基于 html2pdf.js，无需后端，点击即下载 PDF 文件（文件名自动带日期）
- **打印友好**：专门的打印样式，支持浏览器原生打印
- **中文排版优化**：宋体衬线标题 + 无衬线正文，符合法律文书专业风格

---

## 🎨 设计特色

- **庄重大气配色**：深蓝（navy）+ 金色（gold）+ 中国红（crimson）的司法专业配色体系，彰显法律平台的严谨与权威
- **宋体衬线标题**：采用 Noto Serif SC 宋体渲染标题，符合法律文书传统美学
- **法律符号元素**：⚖️ 天平、📜 卷轴、🏛️ 法院、🔨 法槌等法文化图标贯穿始终
- **视觉层次清晰**：
  - 法规卡片左侧红色边线
  - 案件卡片左侧蓝色边线
  - 讨论卡片左侧金色边线
  - 裁判要点黄色高亮卡片
- **响应式布局**：完美适配桌面、平板、手机等多端设备
- **流畅交互**：卡片悬浮动效、滚动导航、数据计数动画、模态框预览

---

## 🚀 部署方式

本项目为**纯静态单页面应用**（单 HTML 文件），无后端依赖，可直接部署到任何静态网站托管平台。

### 方式一：GitHub Pages（推荐，免费）

1. 在 GitHub 创建一个新仓库（Public），例如 `legal-assistant`
2. 将本目录下的三个文件上传到仓库根目录：
   - `index.html`
   - `README.md`
   - `.nojekyll`
3. 进入仓库 **Settings → Pages**
4. 在 **Source** 部分选择 `main` 分支，目录选择 `/ (root)`，点击 **Save**
5. 等待约 1 分钟，即可通过 `https://<你的用户名>.github.io/legal-assistant/` 访问

### 方式二：Vercel（零配置）

1. 登录 [vercel.com](https://vercel.com)
2. 点击 **Add New Project** → 导入你的 GitHub 仓库
3. Framework Preset 选 `Other`，其他保持默认
4. 点击 **Deploy**，数十秒后即可获得可访问链接

### 方式三：Netlify

1. 登录 [netlify.com](https://netlify.com)
2. 直接将本项目文件夹**拖拽到** Netlify 部署区域（无需账号也可匿名部署）
3. 或通过 Sites → Add new site → Import an existing project 从 GitHub 导入

### 方式四：Cloudflare Pages

1. 登录 Cloudflare Dashboard → Pages → Create a project
2. 连接 GitHub 仓库
3. Framework preset 选 `None`，Build command 留空，Output directory 填 `/`
4. 保存并部署

### 方式五：本地预览

直接双击 `index.html` 用浏览器打开即可，无需任何服务器；或使用任意静态服务器：

```bash
# Python 3
python -m http.server 8080

# Node.js (需先安装 serve: npm i -g serve)
serve -p 8080
```

然后访问 `http://localhost:8080`

---

## 📁 项目结构

```
legal-assistant/
├── index.html      # 主应用文件（单文件 HTML/CSS/JS，含全部页面、样式、逻辑、示例数据）
├── README.md       # 项目说明文档（本文件）
└── .nojekyll       # 禁用 GitHub Pages 的 Jekyll 处理，确保静态资源正常加载
```

---

## 🛠️ 技术栈

| 技术 | 用途 | 来源 |
|------|------|------|
| HTML5 | 页面结构 | 原生 |
| Tailwind CSS 3 | UI 样式框架 | CDN |
| Noto Serif/Sans SC | 中文字体（宋体+黑体） | Google Fonts |
| Font Awesome 6.5 | 图标库 | CDN |
| html2pdf.js 0.10 | PDF 导出（浏览器端） | CDN |
| Vanilla JavaScript | 交互逻辑 | 原生，无框架依赖 |

---

## 📊 报告样例结构

生成的《中国法治日报》PDF 包含以下页面：

1. **封面页**：渐变深蓝配色 + 大天平图标 + 日期 + 4 项 KPI（收录法规/今日更新/热点案件/律师观点）
2. **执行摘要页**：4 张 KPI 数字卡 + 自动撰写的中文摘要 + 法规分类 CSS 条形图 + 案件类型标签
3. **每日法律法规更新页**：每项更新带类型/标签/发布机关/状态/内容说明卡片
4. **热门案件判决页**：每起案件含类型/判决结果/法院/裁判要点（黄色高亮）
5. **律师观点页**：每位律师/学者观点带头像/身份/立场标签/点赞数
6. **数据来源与方法说明页**：四大数据源卡片 + 生成方法说明 + 免责声明

---

## 🔌 数据接入说明

当前版本提供完整的示例数据用于演示。如需接入真实数据源，可在 `index.html` 的 `DATA` 对象处进行替换，或通过 `fetch()` 请求真实 API（如国家法律法规数据库、裁判文书网、各律所官网等公开数据源）后将数据赋值给 `DATA` 对象，页面将自动重新渲染。

页面核心数据结构示例（JavaScript）：

```js
DATA = {
  statutes: [   // 法规库
    { title, type, category, issuer, date, effective, status, summary, clauses, highlight }
  ],
  updates: [    // 每日更新
    { title, type, issuer, date, level, desc, status, tag }
  ],
  cases: [      // 热门案件
    { title, type, court, level, date, verdict, result, summary, key, hot }
  ],
  topics: [     // 讨论话题
    { title, heat, replies, views }
  ],
  opinions: [   // 律师观点
    { lawyer, title, avatar, topic, opinion, stance, likes, verified }
  ]
}
```

---

## ⚠️ 免责声明

本平台内容仅供法律研究、信息参考与学术交流使用，**不构成任何法律意见或建议**。所引用案例与观点版权归原作者/发布机关所有。具体法律问题请咨询具有执业资质的律师，或向相关司法机关查询正式文本。开发者不对因依赖本平台内容所产生的任何后果承担法律责任。

---

## 📜 开源协议

MIT License
