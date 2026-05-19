# ⚡️ AI 智能答题助手 (AI Study Copilot) - V2.0 专业版

![](https://img.shields.io/badge/Chrome_Store-v2.0.1-4285F4?style=flat-square&logo=google-chrome&logoColor=white)
![](https://img.shields.io/badge/Firefox_AMO-v2.0.1-FF7139?style=flat-square&logo=firefox-browser&logoColor=white)
![](https://img.shields.io/badge/Model-DeepSeek%20%7C%20OpenAI%20%7C%20Local-blue?style=flat-square)
![](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**一键抓取 · 深度解析 · 学习更轻松**

[功能特性](#-功能特性) • [安装指南](#-安装指南) • [使用说明](#-使用说明) • [赞助与支持](#-赞助与支持) • [免责声明](#-免责声明)

---

<img width="2800" height="1120" alt="顶部图" src="https://github.com/user-attachments/assets/d78510e4-fde8-42ee-9414-73307aab6ded" />

## 📖 项目介绍  

**AI 智能答题助手** (AI Study Copilot) 是一款面向在线学习、职业考证与考前练习的浏览器扩展，基于最新 **DeepSeek V4** 大模型构建。  
不同于静态题库检索，本插件通过**实时 AI 上下文分析**与**深度数据捕获**，可处理变种题、阅读理解与复杂跨学科题目，帮助用户高效检索与解析知识点。

**2.0 版本全面升级**：新增关键词搜索与命中定位、AI 老师体系、自动/手动切片、历史任务管理与智能导出体系，并统一弹窗风格与答案排版，整体体验更紧凑、更高效、更专业。

## ✨ V2.0 核心特性

### 1. 🧠 多模型 AI 引擎  

+ **内置 DeepSeek-V4**：默认开箱即用，适配变种题与逻辑题。  
+ **本地模型直连**：支持 LM Studio，本地算力零成本、无限额、数据不出网。  
+ **自定义 API 接入**：兼容 OpenAI / DeepSeek 官方 Key / 任意兼容接口。  

### 2. 📡 全栈抓包 + 深度扫描  

+ **无感抓取**：自动拦截 AJAX/Fetch 数据流，题目自动入库。  
+ **跨域 Iframe 穿透**：深层嵌套框架也可精准定位题库。  
+ **HTML 深度扫描（VIP功能）**：针对无接口的静态/老旧网页，所见即所得提取。  
+ **解除复制（VIP功能）**：恢复选中/右键/复制能力。  

### 3. 🧩 自动/手动切片（2.0 新增）   

+ **自动切片解析**：数据包过大（题目数量过多）自动分批解析并提示完成进度。  
+ **手动切片**：任意 JSON 一键拆分为两包，方便分批解析与排错。  

### 4. 🔍 关键词搜索与命中定位（2.0 新增） 

+ 抓取列表支持关键词搜索与高亮。  
+ JSON 编辑器内“上一条/下一条”命中跳转。  
+ 命中位置自动居中展示，减少手动滚动。  

### 5. 📚 历史任务中心（2.0 新增）  

+ 自动记录每次 AI 解析任务。  
+ 支持任务搜索、批量导出、批量删除。  
+ 单任务展开可查看**数据包 + AI 解析结果**，支持复制与导出。  

### 6. 📦 智能导出体系（2.0 新增）  

+ **标准导出**：一键导出 JSON / Markdown / CSV。  
+ **AI 智能导出（VIP功能）**：AI 还原题目结构（题干 / 选项 / 答案 / 解析分行输出）。  
+ **官方源限制提醒**：使用官方源时显示剩余次数，超额提示明日刷新或使用自定义模型。  
+ 导出文件统一命名规则：**任务摘要 + 时间戳**。  

### 7. 🎨 统一交互体验  

+ **更紧凑的答案排版**，减少空行。  
+ **统一弹窗系统**：成功/警告/错误风格一致。  
+ **AI 老师体系**：超能学长 / 详解学姐 / 闪电侠  / 思路侠 / 引路者 Socrates / 你的专属私教。  

---

## 📥 安装指南
### 应用商店安装（推荐，自动更新）

| 平台                              | 下载链接                                                     | 说明                              |
| --------------------------------- | ------------------------------------------------------------ | --------------------------------- |
| **Chrome / Edge / 360安全浏览器** | [点击前往 Chrome Web Store](https://chrome.google.com/webstore/detail/eeionpcnekmdcaakfpdmfflejnfkeoab) | 谷歌/Edge/360安全浏览器电脑端专用 |
| **Firefox**                       | [点击前往 Firefox Add-ons](https://addons.mozilla.org/zh-CN/firefox/addon/ai%E6%99%BA%E8%83%BD%E7%AD%94%E9%A2%98%E5%8A%A9%E6%89%8B-%E4%B8%93%E4%B8%9A%E7%89%88/) | 火狐浏览器电脑端专用              |
| **Firefox 移动版**                | [点击前往 Firefox Add-ons 移动版](https://addons.mozilla.org/zh-CN/firefox/addon/ai智能答题助手-专业版/) | 火狐浏览器Andriod 手机/平板端专用 |


> **手动离线安装**：如无法访问商店，可在 Release 页面下载 `.crx` (Chrome) 或 `.xpi` (Firefox) 文件拖拽安装。

---

## 🚀 使用说明
1. **进入题库页面**：打开你需要学习的网课或题库网站。
2. **自动捕获**：
    - 插件会自动静默监听题目数据。
    - 若捕获成功，右下角悬浮球会出现红点数字提醒。
   <img width="130" height="121" alt="image" src="https://github.com/user-attachments/assets/e36173bb-9d1f-4bd2-b601-91d37883ec9b" />
   <img width="1382" height="897" alt="image" src="https://github.com/user-attachments/assets/18376d34-bad8-4ff0-97ac-c4d3b311f683" />   
    
3. **配置模型 (可选)**：
    - 打开设置面板，点击AI自定义模型源，可选择 **“内置模型”**、**“DeepSeek API”**、**“OpenAI”** 或 **“本地模型”**。
    <img width="450" height="682" alt="image" src="https://github.com/user-attachments/assets/b54bb821-cbbe-4826-836d-485ec3f1ff43" />

4. **查看解析**：
    - 点击悬浮球打开面板，勾选需要解析的题目。
    - 点击 **“🚀 发送选中数据给 AI”**。
    <img width="1316" height="836" alt="使用方法1" src="https://github.com/user-attachments/assets/dc9bc2e8-1713-4a04-bca7-c04dee095af4" /> 
    <img width="1440" height="915" alt="image" src="https://github.com/user-attachments/assets/dcf3bc5e-ef55-48dd-ace6-137c03ccfc8b" />

    
5. **深度扫描 (针对无接口页面)**：
    - 如果没有抓到包，在面板中开启 **“HTML 页面深度扫描”** 开关。
   
    <img width="370" height="549" alt="image" src="https://github.com/user-attachments/assets/d3c5739d-b833-48af-a5b1-390f6eb603f1" />
    
    - 点击列表上方的 **“深度扫描”** 按钮。
   
    <img width="2212" height="1552" alt="image" src="https://github.com/user-attachments/assets/585e1aa7-c069-45cc-b1dd-7f766a89a31b" /> 
    <img width="2904" height="1622" alt="image" src="https://github.com/user-attachments/assets/96378348-3b1b-45c6-8c07-43be52baf6bf" />

    
    

---

## ☕ 赞助与支持
本项目的持续维护需要成本。如果您觉得工具对您有帮助，欢迎通过**打赏**支持开发者。

### 💎 赞助回馈方案

**所有 VIP 档位均享有一致的 Pro 级特权：**

✅ **无限模型**：支持 OpenAI / DeepSeek / 本地模型 (LM Studio)  
✅ **超高额度**：内置 AI 额度提升至 **300 次/天**  
✅ **深度扫描**：解锁 HTML 强力扫描，搞定难抓网页  
✅ **解除复制**：一键解锁网页复制/选中/右键限制  
✅ **智能导出**：AI 深度还原题目结构，生成更适合复习的结构化报告  
✅ **私人定制**：解锁 AI 老师体系 + 自定义私教提示词

| 赞助档位 | 权益时长 | 适用场景 & 说明 |
| --- | --- | --- |
| **☕ 日卡** | 24 小时 | **⚡ 临时急用**：全功能解锁，适合临时突击或尝鲜体验。 |
| **🥤 周卡** | 7 天 | **📅 短期冲刺**：适合期末周复习，一周内无限畅享所有功能。 |
| **🍱 月卡** | 30 天 | **💪 习惯养成**：高性价比之选，满足一个月的日常学习需求。 |
| **🍲 季卡** | 90 天 | **📚 备考神器**：适合考研/考公/考证专项复习，稳定陪伴一整季。 |
| **🚀 半年卡** | 180 天 | **💰 超值优惠**：一次赞助管半年，无需频繁续费，省心更省钱。 |
| **👑 年卡** | 365 天 | **🏆 铁粉专享**：折合每天仅需几分钱，全年无忧学习。 |

---

> **特别说明**：
> 1. **免费福利**：连接 **本地模型 (LM Studio)** 可 **免费无限制** 使用，无需赞助！
> 2. **普通用户**：每日享有 10 次免费内置 AI 解析额度。
> 3. **权益找回**：请务必在插件底部备份您的 **账户 ID**，这是您恢复权益的唯一凭证。

---

## ⚠️ 免责声明

在使用本软件前，请务必仔细阅读以下条款：

1. **辅助学习工具**：本软件仅用于辅助知识检索和理解。**严禁**将本软件用于任何形式的违反法律法规、违反校规校纪或第三方平台规则的行为（包括但不限于考试作弊）。
2. **技术中立**：开发者仅提供数据处理技术。用户利用本软件在第三方平台进行的任何操作，其后果完全由用户自行承担。
3. **数据安全**：本软件仅在用户主动操作时处理题目文本，**绝不**收集用户的账号密码、Cookie 或个人隐私信息。Key 仅保存在本地浏览器。
4. **合规使用**：请勿利用本软件批量抓取他人拥有知识产权的题库数据用于商业牟利。

---

## 🛠️ 技术栈
+ **前端核心**: Vanilla JavaScript (ES6+), HTML5, CSS3
+ **扩展框架**: Chrome Extension Manifest V3
+ **通信机制**: `chrome.runtime`, `window.postMessage`, `MessageChannel`
+ **网络拦截**: `XMLHttpRequest` Proxy, `Fetch` Proxy (Silent Bypass)
+ **AI 接口**: Multi-Provider Support (Built-in Proxy / OpenAI / LM Studio)

---

## 📄 License
[MIT License](LICENSE) © 2026 Hx0 Team
