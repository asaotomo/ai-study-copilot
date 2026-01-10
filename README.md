# ⚡️ AI 智能答题助手 (AI Study Copilot) - V1.2 专业版

![](https://img.shields.io/badge/Chrome_Store-v1.2.1-4285F4?style=flat-square&logo=google-chrome&logoColor=white)
![](https://img.shields.io/badge/Firefox_AMO-v1.2.1-FF7139?style=flat-square&logo=firefox-browser&logoColor=white)
![](https://img.shields.io/badge/Model-DeepSeek%20%7C%20OpenAI%20%7C%20Local-blue?style=flat-square)
![](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**一键抓取 · 多模型支持 · 权益可找回 · 学习更轻松**

[功能特性](#-功能特性) • [安装指南](#-安装指南) • [使用说明](#-使用说明) • [赞助与支持](#-赞助与支持) • [免责声明](#-免责声明)

---

<img width="2800" height="1120" alt="顶部图" src="https://github.com/user-attachments/assets/d78510e4-fde8-42ee-9414-73307aab6ded" />

## 📖 项目介绍
**AI 智能答题助手** (AI Study Copilot) 是一款专为在线学习设计的浏览器扩展。V1.2 版本迎来重大升级，打破模型限制，不仅内置 **DeepSeek** 智能引擎，更开放支持 **OpenAI** 及 **本地大模型 (LM Studio)**。

不同于传统的题库匹配软件，本插件不依赖静态题库，而是通过**实时 AI 分析**，能够处理全新的题目、变种题以及复杂的阅读理解题。我们秉持“技术辅助学习”的理念，致力于将繁琐的资料检索过程自动化。

## ✨ V1.2 核心特性

### 1. ♾️ 模型源自由切换 (New)
+ **本地模型无限刷**：支持连接本地 **LM Studio**，数据不上云，零成本、无限制、隐私更安全！
+ **自定义 API**：兼容 OpenAI 及任意第三方接口 (OneAPI/NewAPI)，想用什么模型由你决定。
+ **内置 DeepSeek**：无需配置，开箱即用（VIP 尊享每日 300 次极速解析）。

### 2. 🆔 账户权益保障 (New)
+ **ID 备份与恢复**：全新上线账户管理面板，支持查看与备份专属账户 ID。
+ **权益不丢失**：无论是更换电脑还是重装系统，只需填入旧 ID，会员权益一键恢复。

### 3. 🛡️ 静默抓包引擎
+ **无感抓取**：采用全新的旁路监听技术，自动拦截网页题目数据（AJAX/Fetch）。
+ **更强兼容**：完美支持跨域 Iframe 及各种复杂的动态加载题库，抓包更稳、更隐蔽。

### 4. 🔍 HTML 深度扫描 (VIP)
+ 针对没有数据接口的老旧静态网页，提供 **DOM 深度扫描** 模式。
+ 直接从网页可见区域提取题目文本，支持 OCR 无法处理的复杂排版。

### 5. 👆 极简交互体验
+ **数据看板**：新增 AI 生成耗时统计与响应时间显示，精准把控答题节奏。
+ **智能高亮**：自动识别题型（[单选]、[多选]、[填空]），并使用彩色标签高亮显示。
+ **美观模态框**：全新设计的交互弹窗，视觉更统一，操作更丝滑。

---

## 📥 安装指南
### 应用商店安装（推荐，自动更新）
| 平台 | 下载链接 | 说明 |
| :--- | :--- | :--- |
| **Chrome / Edge / 360安全浏览器** | [点击前往 Chrome Web Store](https://chrome.google.com/webstore/detail/eeionpcnekmdcaakfpdmfflejnfkeoab) | 谷歌/Edge/360安全浏览器专用 |
| **Firefox** | [点击前往 Firefox Add-ons](https://addons.mozilla.org/zh-CN/firefox/addon/ai智能答题助手-专业版/) | 火狐浏览器专用 |

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
    <img width="1452" height="811" alt="image" src="https://github.com/user-attachments/assets/293f5d0d-2374-4a2a-a8f5-f3c6b62ebf74" />
    
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

✅ **超高额度**：内置 AI 额度提升至 **300次/天**

✅ **深度扫描**：解锁 HTML 强力扫描，搞定难抓网页

✅ **私人定制**：支持自定义 AI 提示词 (Prompt)

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
[MIT License](LICENSE) © 2026 Hx0 Security Team
