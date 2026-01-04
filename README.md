# ⚡️ AI 智能答题助手 (AI Study Copilot)

![](https://img.shields.io/badge/Chrome_Store-v1.0.0-4285F4?style=flat-square&logo=google-chrome&logoColor=white)
![](https://img.shields.io/badge/Firefox_AMO-v1.0.0-FF7139?style=flat-square&logo=firefox-browser&logoColor=white)
![](https://img.shields.io/badge/Model-DeepSeek_V3-blue?style=flat-square)
![](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**全能抓取 · 深度解析 · 辅助学习**

[功能特性](#-功能特性) • [安装指南](#-安装指南) • [使用说明](#-使用说明) • [赞助支持](#-赞助支持) • [免责声明](#-免责声明)

---


<img width="2800" height="1120" alt="顶部图" src="https://github.com/user-attachments/assets/d78510e4-fde8-42ee-9414-73307aab6ded" />


## 📖 项目介绍
**AI 智能答题助手** (AI Study Copilot)是一款专为在线学习设计的浏览器扩展。它利用最新的 **DeepSeek V3.2** 人工智能模型，帮助用户快速解析网页上的疑难题目。

不同于传统的题库匹配软件，本插件不依赖静态题库，而是通过**实时 AI 分析**，能够处理全新的题目、变种题以及复杂的阅读理解题。我们秉持“技术辅助学习”的理念，致力于将繁琐的资料检索过程自动化。

## ✨ 功能特性
### 1. 🛡️ 强力数据捕获
+ **无感抓取**：自动拦截网页传输的题目数据（AJAX/Fetch），无需手动复制。
+ **Iframe 穿透**：独家技术支持，能够穿透嵌套的 Iframe 页面精准获取内嵌题库数据。

### 2. 🔍 HTML 深度扫描 (VIP)
+ 针对没有数据接口的老旧静态网页，提供**DOM 深度扫描**模式。
+ 直接从网页源码中提取题目文本，支持 OCR 无法处理的复杂排版。

### 3. 🧠 DeepSeek 智能解析
+ 集成 **DeepSeek-Chat** 模型，解析准确率高，响应速度快。
+ **智能高亮**：自动识别题型（[单选]、[多选]、[填空]），并使用彩色标签高亮显示。

### 4. 🎨 高度个性化
+ **BYOK 模式**：支持填入自己的 DeepSeek API Key，解除所有使用限制，直接请求官方接口。
+ **自定义 Prompt**：支持修改 AI 的系统提示词（如：“只给答案选项”、“详细解释知识点”）。

### 5. 👆 极简交互
+ **悬浮球设计**：拖拽式悬浮球，不占用页面空间，抓到题目自动变色提醒。
+ **一键复制**：解析结果支持一键复制，格式完美适配各种笔记软件。

<img width="880" height="560" alt="小宣传图" src="https://github.com/user-attachments/assets/f5dae6e3-fa5a-4cf2-b53e-6eb1f71dec2b" />

---

## 📥 安装指南
### 应用商店安装（推荐，自动更新）
| 平台 | 下载链接 | 说明 |
| :--- | :--- | :--- |
| **Chrome** | [点击前往 Chrome Web Store](https://chrome.google.com/webstore/detail/eeionpcnekmdcaakfpdmfflejnfkeoab) | 谷歌浏览器专用 |
| **Firefox** | [点击前往 Firefox Add-ons](https://addons.mozilla.org/zh-CN/firefox/addon/ai智能答题助手-专业版/) | 火狐浏览器专用 |

---

## 🚀 使用说明
1. **进入题库页面**：打开你需要学习的网课或题库网站。
3. **自动捕获**：
    - 此时插件会自动监听题目数据。
    - 若捕获成功，右下角悬浮球会出现红点数字提醒。
    <img width="1382" height="897" alt="image" src="https://github.com/user-attachments/assets/18376d34-bad8-4ff0-97ac-c4d3b311f683" />
    
4. **查看解析**：
    - 点击悬浮球打开面板。
    - 勾选需要解析的题目数据包。
    - 点击 **“****🚀**** 发送选中数据给 AI”**。
    <img width="1316" height="836" alt="使用方法1" src="https://github.com/user-attachments/assets/dc9bc2e8-1713-4a04-bca7-c04dee095af4" />
    <img width="1316" height="836" alt="使用方法2" src="https://github.com/user-attachments/assets/add633cb-4697-4a26-b821-1fd69cf8c064" />
5. **深度扫描 (针对无接口页面)**：
    - 如果没有抓到包，在面板中开启 **“HTML 页面深度扫描”** 开关。
   
   <img width="1391" height="868" alt="image" src="https://github.com/user-attachments/assets/703fed56-06bb-48ee-b944-a8d0c2649385" />
    
    - 点击列表上方的 **“深度扫描”** 按钮。
    
    <img width="1331" height="877" alt="image" src="https://github.com/user-attachments/assets/71a9acea-71b0-480d-8ece-0d4f8f3950cd" />
    
    <img width="1452" height="811" alt="image" src="https://github.com/user-attachments/assets/293f5d0d-2374-4a2a-a8f5-f3c6b62ebf74" />


---

## ☕ 赞助与支持
本项目的服务器维护与 AI 接口调用需要持续的成本投入。如果您觉得工具对您有帮助，欢迎通过**打赏/赞助**的方式支持开发者。

**赞助回馈权益：**

| 赞助档位 | 权益时长 | 特权说明 |
| :--- | :--- | :--- |
| **☕** **日卡** | 24 小时 | 解锁24小时高级解析权限（300次/天），支持深度扫描模式，大幅提升资料检索效率。 |
| **🥤** **周卡** | 7 天 | 连续7天解锁 AI 智能辅助，开启 HTML 深度扫描功能，轻松应对各类复杂网页的知识点提取。 |
| **🍱** **月卡** | 30 天 | 解锁整月 VIP 权益，支持自定义 AI 提示词（Prompt），让 AI 按照您的学习习惯进行解析和辅导。 |
| **🍲** **季卡** | 90 天 | 解锁整整一个季度 (90天) 的高级解析权限。非常适合考研、考公或考证的专项复习冲刺阶段，稳定陪伴您的每一天。 |
| **🚀** **半年卡** | 180 天 | 一次赞助，解锁整个学期（180天）的高级功能。稳定支持 DeepSeek 接口调用，保障您的长期学习进度。 |
| **👑** **年度铁粉** | 365 天 | 解锁整整一年 (365天) 的所有 Pro 权益（含深度扫描/BYOK模式）。您的支持将用于分摊昂贵的 GPU 算力成本，感谢有你！ |


> **特别说明**：
>
> 1. 普通用户每日享有 10 次免费 AI 解析额度。
> 2. 拥有自己 API Key 的用户可**免费无限制**使用 BYOK 模式。
> 3. 打赏金额仅用于抵扣服务器与接口成本。
>

---

## ⚠️ 免责声明 (User Agreement)
在使用本软件前，请务必仔细阅读以下条款：

1. **辅助学习工具**：本软件开发的初衷是辅助用户进行知识检索和解析，帮助理解知识点。**严禁**将本软件用于任何形式的违反法律法规、违反校规校纪或第三方平台规则的行为（包括但不限于考试作弊）。
2. **技术中立**：开发者仅提供数据处理与 AI 接口调用的技术工具。用户利用本软件在第三方平台进行的任何操作，其后果完全由用户自行承担。
3. **数据安全**：本软件仅在用户主动操作时处理题目文本数据，**绝不**收集用户的账号密码、Cookie 或个人隐私信息。
4. **合规使用**：请勿利用本软件批量抓取他人拥有知识产权的题库数据用于商业牟利。

---

## 🛠️ 技术栈
+ **前端核心**: Vanilla JavaScript (ES6+), HTML5, CSS3
+ **扩展框架**: Chrome Extension Manifest V3
+ **通信机制**: `chrome.runtime`, `window.postMessage`, `MessageChannel`
+ **网络拦截**: `XMLHttpRequest` Proxy, `Fetch` Proxy
+ **AI 接口**: DeepSeek API (OpenAI Compatible)

---

## 📄 License
[MIT License](LICENSE) © 2025 AI Smart Study Assistant Team

