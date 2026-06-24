# 项目管理系统

<!-- SIUSER-REPO-GUIDE:START -->
## 项目介绍 / Project Introduction

### 中文
项目管理实践：沉淀 AI 工作流、任务追踪和协作管理方法。

### English
Project management practice repo for AI workflows, task tracking, and collaboration methods.

## 使用方式 / Usage

### 中文
1. 先克隆仓库并安装 Node 依赖。
2. 根据 `package.json` 中的 scripts 启动开发、构建或测试命令。
3. 如果有在线入口，先对照线上页面理解最终效果，再回到源码修改。

### English
1. Clone the repository and install the Node dependencies.
2. Use the scripts in `package.json` for development, build, or tests.
3. If a live link exists, review the deployed page first, then make source changes.

## 入口与元信息 / Entry Points & Metadata

- GitHub 仓库 / Repository: https://github.com/siuserxiaowei/project-management
- Live / 在线入口：https://project-management-bice-nu.vercel.app
- 默认分支 / Default branch: `main`
- 主要语言 / Primary language: `JavaScript`
- 可见性 / Visibility: `public`
- 仓库类型 / Repository type: `source`

## 本地运行 / Local Run

```bash
git clone https://github.com/siuserxiaowei/project-management.git
cd project-management
npm install
npm run dev
npm run start
```

## 仓库结构 / Repository Map

| 路径 / Path | 中文说明 | English |
| --- | --- | --- |
| `README.md` | 项目入口说明，先读这里。 | Main project entry point and orientation. |
| `package.json` | Node/前端项目配置、依赖和脚本。 | Node/frontend dependencies and scripts. |
| `public` | 公开静态资源。 | Public static assets. |
| `scripts` | 构建、同步、生成或维护脚本。 | Build, sync, generation, or maintenance scripts. |
| `.claude` | 项目文件或目录。 | Project file or directory. |
| `api` | 项目文件或目录。 | Project file or directory. |
| `config` | 项目文件或目录。 | Project file or directory. |
| `.env.example` | 项目文件或目录。 | Project file or directory. |
| `.gitignore` | 项目文件或目录。 | Project file or directory. |
| `.vercelignore` | 项目文件或目录。 | Project file or directory. |
| `CHEAT_SHEET.md` | 项目文件或目录。 | Project file or directory. |
| `deploy.sh` | 项目文件或目录。 | Project file or directory. |

## 维护备注 / Maintenance Notes

- 中文：当项目目标、在线入口、运行命令或目录结构变化时，同步更新本说明。
- English: Keep this guide updated when the project purpose, live link, run commands, or structure changes.
- 中文：修改代码、数据或生成页面后，优先运行相关构建、测试或校验命令。
- English: After changing code, data, or generated pages, run the relevant build, test, or validation command.

## 安全与隐私 / Safety & Privacy

- 中文：不要提交 API key、token、密码、cookie、私有链接或内部账号资料。
- English: Do not commit API keys, tokens, passwords, cookies, private URLs, or internal account data.
- 中文：公开 GitHub Pages 前，确认资料已脱敏并允许公开。
- English: Before publishing GitHub Pages output, confirm the material is redacted and cleared for public release.
<!-- SIUSER-REPO-GUIDE:END -->



<!-- SIUSER-SEO-INTRO:START -->

## 项目介绍 / Project Introduction

**中文介绍**：项目管理实践仓库，整理任务拆解、进度跟踪、协作流程和 AI 辅助项目推进方法。

**English**: A project-management practice repo for task breakdown, progress tracking, collaboration workflows, and AI-assisted delivery.

**SEO 关键词 / SEO Keywords**: project management, AI workflow, task tracking, collaboration, 项目管理

<!-- SIUSER-SEO-INTRO:END -->

一个简单易用的项目管理系统，专为流量接单和中台分销业务设计。

## 功能特点

- 📋 **项目管理**：创建、跟踪、管理项目全生命周期
- 👥 **角色管理**：客户、写手信息管理
- 💰 **财务跟踪**：报价、成本、利润计算
- ⏰ **时间线**：项目状态变更历史记录
- 📊 **数据统计**：项目总数、收入、利润统计
- 🎨 **简洁界面**：响应式设计，支持移动端访问

## 系统架构

- **前端**：HTML + Bootstrap + JavaScript（原生）
- **后端**：Node.js + Express
- **数据库**：SQLite（轻量级，无需额外配置）

## 快速开始

### 1. 安装依赖

```bash
npm install
```

### 2. 初始化数据库

```bash
npm run init-db
```

### 3. 启动服务

```bash
npm start
```

或者开发模式（自动重启）：

```bash
npm run dev
```

### 4. 访问系统

打开浏览器访问：http://localhost:3000

## 项目状态流程

```
待接单 → 已接单 → 写手分配 → 写作中 → 初审 → 修改中 → 终审 → 已交付 → 已结算
```

## 数据结构

### 项目信息
- 基本信息：标题、类型、描述
- 人员信息：客户、写手
- 时间信息：创建时间、截止时间
- 财务信息：客户报价、写手成本、利润
- 项目详情：字数、难度等级
- 状态跟踪：当前状态、时间线

### 客户信息
- 姓名、联系方式、公司

### 写手信息
- 姓名、专业领域、联系方式、费率

## 界面预览

- **首页仪表板**：项目统计概览
- **项目卡片**：简洁的项目信息展示
- **新建项目**：友好的表单界面
- **项目详情**：完整的项目信息和时间线
- **状态管理**：一键更新项目状态

## 特色功能

1. **智能统计**：实时计算总收入、总利润
2. **状态追踪**：完整的项目状态变更历史
3. **响应式设计**：适配各种设备屏幕
4. **操作简单**：所有操作都是点击式，无需复杂学习

## 扩展说明

关于MCP服务器：
- `yamadashy/repomix`：项目初始化工具
- `oraios/serena`：AI语言操作增强
- `servers/src/filesystem`：文件系统操作

这些是Claude Desktop的扩展服务，需要在Claude Desktop的配置文件中添加，不是项目代码的一部分。

## 技术支持

如需添加新功能或修改现有功能，请参考代码注释或联系开发者。

<!-- SIUSER-CONTACT:START -->

## 联系我 / Contact

想交流 AI 工具、内容自动化、SEO、私域增长或项目合作，可以扫码加我微信。

For collaboration on AI tools, content automation, SEO, private-domain growth, or product experiments, scan the WeChat QR code below.

<img src="https://raw.githubusercontent.com/siuserxiaowei/siuserxiaowei/main/assets/contact/wechat-qrcode.jpg" width="180" alt="WeChat QR code / 微信二维码" />

**关键词 / Keywords**: project management, AI workflow, task tracking, collaboration, AI tools, AI automation, GitHub Pages, SEO

<!-- SIUSER-CONTACT:END -->
