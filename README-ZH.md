# **Awesome Claude Skills (卓越 Claude 技能精選)**

這是一份精選的實用 **Claude 技能 (Claude Skills)** 清單，旨在提升你在 Claude.ai、Claude Code 以及 Claude API 上的生產力。

**想要擁有不只是生成文字的技能嗎？** Claude 可以傳送電子郵件、建立 Issue、在 Slack 發文，並在超過 1000 個應用程式中執行操作。[查看方法 →](https://www.google.com/search?q=./connect/)

## ---

**快速入門：將 Claude 連接到 500+ 個應用程式**

**connect-apps** 外掛程式讓 Claude 能夠執行真實的操作——傳送郵件、建立 Issue、在 Slack 發文。它負責處理身分驗證，並在底層透過 Composio 連接到 500 多個應用程式。

### **1\. 安裝外掛程式**

Bash

claude \--plugin-dir ./connect-apps-plugin

### **2\. 執行設定**

/connect-apps:setup

在要求時貼上你的 API 金鑰。（可在 [platform.composio.dev](https://platform.composio.dev/?utm_source=Github&utm_content=AwesomeSkills) 獲取免費金鑰）

### **3\. 重啟並嘗試**

Bash

exit  
claude

**想要擁有不只是生成文字的技能嗎？** Claude 可以傳送電子郵件、建立 Issue、在 Slack 發文，並在超過 1000 個應用程式中執行操作。[查看方法 →](https://www.google.com/search?q=./connect/)

如果你收到了電子郵件，代表 Claude 現已成功連接到 500 多個應用程式。

[**查看所有支援的應用程式 →**](https://composio.dev/toolkits)

## ---

**目錄**

* [什麼是 Claude 技能？](https://www.google.com/search?q=%23what-are-claude-skills)  
* [技能分類](https://www.google.com/search?q=%23skills)  
  * [文件處理](https://www.google.com/search?q=%23document-processing)  
  * [開發與程式碼工具](https://www.google.com/search?q=%23development--code-tools)  
  * [數據與分析](https://www.google.com/search?q=%23data--analysis)  
  * [商業與行銷](https://www.google.com/search?q=%23business--marketing)  
  * [溝通與寫作](https://www.google.com/search?q=%23communication--writing)  
  * [創意與媒體](https://www.google.com/search?q=%23creative--media)  
  * [生產力與組織](https://www.google.com/search?q=%23productivity--organization)  
  * [協作與專案管理](https://www.google.com/search?q=%23collaboration--project-management)  
  * [安全性與系統](https://www.google.com/search?q=%23security--systems)  
  * [透過 Composio 進行應用程式自動化](https://www.google.com/search?q=%23app-automation-via-composio)  
* [入門指南](https://www.google.com/search?q=%23getting-started)  
* [建立技能](https://www.google.com/search?q=%23creating-skills)  
* [參與貢獻](https://www.google.com/search?q=%23contributing)  
* [相關資源](https://www.google.com/search?q=%23resources)  
* [授權條款](https://www.google.com/search?q=%23license)

## ---

**什麼是 Claude 技能？**

**Claude 技能 (Claude Skills)** 是可自定義的工作流，用於教導 Claude 如何根據你的獨特需求執行特定任務。技能使 Claude 能夠在所有 Claude 平台上，以可重複且標準化的方式執行任務。

## ---

**技能清單**

### **文件處理 (Document Processing)**

* [docx](https://github.com/anthropics/skills/tree/main/skills/docx) \- 建立、編輯、分析 Word 文件，支援修訂追蹤、評論與格式設定。  
* [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) \- 提取文字、表格、元數據，合併並標註 PDF。  
* [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) \- 讀取、生成及調整投影片、版面配置與模板。  
* [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) \- 試算表操作：公式、圖表、數據轉換。  
* [Markdown to EPUB Converter](https://github.com/smerchek/claude-epub-skill) \- 將 Markdown 文件與對話摘要轉換為專業的 EPUB 電子書檔案。*作者：[@smerchek](https://github.com/smerchek)*

### **開發與程式碼工具 (Development & Code Tools)**

* [artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder) \- 一套工具，用於使用現代前端技術（React, Tailwind CSS, shadcn/ui）在 claude.ai 建立精細的多組件 HTML Artifacts。  
* [aws-skills](https://github.com/zxkane/aws-skills) \- 遵循 CDK 最佳實踐的 AWS 開發、成本優化 MCP 伺服器，以及無伺服器/事件驅動架構模式。  
* [Changelog Generator](https://www.google.com/search?q=./changelog-generator/) \- 透過分析 Git commit 紀錄，將技術性的提交內容轉換為面向客戶的友善發佈說明，自動生成更新日誌。  
* [Claude Code Terminal Title](https://github.com/bluzername/claude-code-terminal-title) \- 為每個 Claude-Code 終端機視窗提供動態標題，描述正在進行的工作，讓你不會混淆視窗。  
* [D3.js Visualization](https://github.com/chrisvoncsefalvay/claude-d3js-skill) \- 教導 Claude 生成 D3 圖表與互動式數據視覺化。*作者：[@chrisvoncsefalvay](https://github.com/chrisvoncsefalvay)*  
* [FFUF Web Fuzzing](https://github.com/jthack/ffuf_claude_skill) \- 整合 ffuf 網路模糊測試工具，讓 Claude 執行模糊測試並分析漏洞結果。*作者：[@jthack](https://github.com/jthack)*  
* [finishing-a-development-branch](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) \- 透過提供清晰的選項並處理選定的工作流，引導開發工作的收尾。  
* [iOS Simulator](https://github.com/conorluddy/ios-simulator-skill) \- 使 Claude 能夠與 iOS 模擬器互動，進行 iOS 應用程式的測試與偵錯。*作者：[@conorluddy](https://github.com/conorluddy)*  
* [jules](https://github.com/sanjay3290/ai-skills/tree/main/skills/jules) \- 將編碼任務委託給 Google Jules AI 代理，在 GitHub 儲存庫上進行異步臭蟲修復、文檔編寫、測試與功能實作。*作者：[@sanjay3290](https://github.com/sanjay3290)*  
* [LangSmith Fetch](https://www.google.com/search?q=./langsmith-fetch/) \- 透過自動獲取並分析 LangSmith Studio 的執行軌跡來調試 LangChain 和 LangGraph 代理。這是 Claude Code 的第一個 AI 可觀測性技能。*作者：[@OthmanAdi](https://github.com/OthmanAdi)*  
* [MCP Builder](https://www.google.com/search?q=./mcp-builder/) \- 引導建立高品質的 MCP (模型上下文協定) 伺服器，使用 Python 或 TypeScript 將外部 API 和服務與 LLM 整合。  
* [move-code-quality-skill](https://github.com/1NickPappas/move-code-quality-skill) \- 根據 Move Book 官方程式碼品質清單分析 Move 語言套件，確保符合 Move 2024 版本規範。  
* [Playwright Browser Automation](https://github.com/lackeyjb/playwright-skill) \- 透過模型調用的 Playwright 自動化，用於測試與驗證 Web 應用程式。*作者：[@lackeyjb](https://github.com/lackeyjb)*  
* [prompt-engineering](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/customaize-agent/skills/prompt-engineering) \- 教導知名的提示工程技術與模式，包括 Anthropic 最佳實踐與代理說服原則。  
* [pypict-claude-skill](https://github.com/omkamal/pypict-claude-skill) \- 使用 PICT (兩兩獨立組合測試) 為需求或程式碼設計全面的測試案例，生成優化的測試套件。  
* [reddit-fetch](https://github.com/ykdojo/claude-code-tips/tree/main/skills/reddit-fetch) \- 當 WebFetch 被封鎖或返回 403 錯誤時，透過 Gemini CLI 獲取 Reddit 內容。  
* [Skill Creator](https://www.google.com/search?q=./skill-creator/) \- 為建立有效的 Claude 技能提供指導，透過專業知識、工作流和工具整合來擴展能力。  
* [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) \- 幾分鐘內自動將任何文件網站轉換為 Claude AI 技能。*作者：[@yusufkaraaslan](https://github.com/yusufkaraaslan)*  
* [software-architecture](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/ddd/skills/software-architecture) \- 實作設計模式，包括整潔架構 (Clean Architecture)、SOLID 原則以及全面的軟體設計最佳實踐。  
* [subagent-driven-development](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/sadd/skills/subagent-driven-development) \- 為單個任務派發獨立的子代理，並在迭代之間進行程式碼審查檢查點，以實現快速且受控的開發。  
* [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) \- 在編寫實作程式碼之前，用於實作任何功能或臭蟲修復。  
* [using-git-worktrees](https://github.com/obra/superpowers/blob/main/skills/using-git-worktrees/) \- 建立隔離的 Git 工作樹，具備智能目錄選擇與安全性驗證。  
* [Connect](https://www.google.com/search?q=./connect/) \- 將 Claude 連接到任何應用程式。傳送電子郵件、建立 Issue、發布訊息、更新資料庫——在 Gmail、Slack、GitHub、Notion 等 1000 多個服務中執行真實操作。  
* [Webapp Testing](https://www.google.com/search?q=./webapp-testing/) \- 使用 Playwright 測試本地 Web 應用程式，以驗證前端功能、調試 UI 行為並擷取螢幕截圖。

### **數據與分析 (Data & Analysis)**

* [CSV Data Summarizer](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) \- 自動分析 CSV 檔案並生成包含視覺化效果的綜合洞察，無需用戶提示。*作者：[@coffeefuelbump](https://github.com/coffeefuelbump)*  
* [deep-research](https://github.com/sanjay3290/ai-skills/tree/main/skills/deep-research) \- 使用 Gemini Deep Research 代理執行自主的多步驟研究，進行市場分析、競爭對手研究和文獻綜述。*作者：[@sanjay3290](https://github.com/sanjay3290)*  
* [postgres](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres) \- 對 PostgreSQL 資料庫執行安全的唯讀 SQL 查詢，支援多連接與深度防禦安全機制。*作者：[@sanjay3290](https://github.com/sanjay3290)*  
* [root-cause-tracing](https://github.com/obra/superpowers/tree/main/skills/root-cause-tracing) \- 當執行深處發生錯誤且你需要溯源以尋找原始觸發因素時使用。

### **商業與行銷 (Business & Marketing)**

* [Brand Guidelines](https://www.google.com/search?q=./brand-guidelines/) \- 將 Anthropic 官方品牌顏色與字體應用於 Artifacts，確保視覺識別一致與專業設計標準。  
* [Competitive Ads Extractor](https://www.google.com/search?q=./competitive-ads-extractor/) \- 從廣告庫中提取並分析競爭對手的廣告，以了解引起共鳴的訊息傳遞與創意方法。  
* [Domain Name Brainstormer](https://www.google.com/search?q=./domain-name-brainstormer/) \- 生成具創意的網域名稱構想，並檢查多個 TLD（包括 .com, .io, .dev, 和 .ai 擴展名）的可用性。  
* [Internal Comms](https://www.google.com/search?q=./internal-comms/) \- 協助編寫內部溝通文件，包括第三方更新、公司通訊、常見問答、進度報告以及使用公司特定格式的專案更新。  
* [Lead Research Assistant](https://www.google.com/search?q=./lead-research-assistant/) \- 透過分析你的產品、搜尋目標公司並提供可執行的推廣策略，識別並篩選高品質的潛在客戶。

### **溝通與寫作 (Communication & Writing)**

* [article-extractor](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/article-extractor) \- 從網頁中提取完整的文章文字與元數據。  
* [brainstorming](https://github.com/obra/superpowers/tree/main/skills/brainstorming) \- 透過結構化提問與替代方案探索，將初步構思轉化為完整的設計。  
* [Content Research Writer](https://www.google.com/search?q=./content-research-writer/) \- 透過進行研究、添加引用、改進引子並提供逐段反饋，協助編寫高品質內容。  
* [family-history-research](https://github.com/emaynard/claude-family-history-research-skill) \- 為規劃家族歷史與族譜研究專案提供協助。  
* [Meeting Insights Analyzer](https://www.google.com/search?q=./meeting-insights-analyzer/) \- 分析會議記錄以揭示行為模式，包括衝突規避、發言比例、贅詞以及領導風格。  
* [NotebookLM Integration](https://github.com/PleasePrompto/notebooklm-skill) \- 讓 Claude Code 直接與 NotebookLM 對話，僅根據上傳的文件提供有據可依的回答。*作者：[@PleasePrompto](https://github.com/PleasePrompto)*  
* [Twitter Algorithm Optimizer](https://www.google.com/search?q=./twitter-algorithm-optimizer/) \- 使用 Twitter 的開源算法洞察來分析並優化推文，以獲得最大觸及率。重寫並編輯推文以提高互動與曝光率。

### **創意與媒體 (Creative & Media)**

* [Canvas Design](https://www.google.com/search?q=./canvas-design/) \- 使用設計哲學與美學原則，在 PNG 和 PDF 文件中為海報、設計和靜態作品建立視覺藝術。  
* [imagen](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) \- 使用 Google Gemini 的圖像生成 API 為 UI 原型、圖標、插圖和視覺資產生成圖像。*作者：[@sanjay3290](https://github.com/sanjay3290)*  
* [Image Enhancer](https://www.google.com/search?q=./image-enhancer/) \- 透過提高解析度、銳利度和清晰度來改進圖像與螢幕截圖品質，適用於專業簡報與文檔。  
* [Slack GIF Creator](https://www.google.com/search?q=./slack-gif-creator/) \- 建立針對 Slack 優化的動畫 GIF，具備尺寸限制驗證器與可組合的動畫原語。  
* [Theme Factory](https://www.google.com/search?q=./theme-factory/) \- 為 Artifacts（包括投影片、文檔、報告和 HTML 登陸頁面）套用專業字體與顏色主題，內建 10 種預設主題。  
* [Video Downloader](https://www.google.com/search?q=./video-downloader/) \- 從 YouTube 等平台下載影片用於離線觀看、編輯或存檔，支援多種格式與品質選項。  
* [youtube-transcript](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/youtube-transcript) \- 獲取 YouTube 影片逐字稿並準備摘要。

### **生產力與組織 (Productivity & Organization)**

* [File Organizer](https://www.google.com/search?q=./file-organizer/) \- 透過理解語境、尋找重複檔案並建議更好的組織結構，智能地整理檔案與資料夾。  
* [Invoice Organizer](https://www.google.com/search?q=./invoice-organizer/) \- 透過讀取檔案、提取資訊與統一命名，自動整理發票與收據以進行稅務申報準備。  
* [kaizen](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/kaizen/skills/kaizen) \- 基於日本改善 (Kaizen) 哲學與精實生產 (Lean) 方法論，應用具備多種分析方法的持續改進流程。  
* [n8n-skills](https://github.com/haunchen/n8n-skills) \- 使 AI 助手能夠直接理解並操作 n8n 工作流。  
* [Raffle Winner Picker](https://www.google.com/search?q=./raffle-winner-picker/) \- 使用具備密碼學安全隨機性的方法，從名單、試算表或 Google 表單中隨機抽選抽獎活動的中獎者。  
* [Tailored Resume Generator](https://www.google.com/search?q=./tailored-resume-generator/) \- 分析職位描述並生成量身定制的履歷，突出相關經驗、技能與成就，以最大化面試機會。  
* [ship-learn-next](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/ship-learn-next) \- 協助根據反饋迴圈迭代下一個該構建或學習什麼內容的技能。  
* [tapestry](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/tapestry) \- 將相關文件互連並總結為知識網絡。

### **協作與專案管理 (Collaboration & Project Management)**

* [git-pushing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/git-pushing) \- 自動化 Git 操作與儲存庫交互。  
* [google-workspace-skills](https://github.com/sanjay3290/ai-skills/tree/main/skills) \- 一套 Google Workspace 整合：Gmail、日曆、聊天、文檔、試算表、簡報和雲端硬碟，支援跨平台 OAuth。*作者：[@sanjay3290](https://github.com/sanjay3290)*  
* [outline](https://github.com/sanjay3290/ai-skills/tree/main/skills/outline) \- 在 Outline wiki 實例（雲端或自託管）中搜尋、讀取、建立與管理文檔。*作者：[@sanjay3290](https://github.com/sanjay3290)*  
* [review-implementing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/review-implementing) \- 評估程式碼實作計劃並與規格對齊。  
* [test-fixing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/test-fixing) \- 檢測失敗的測試並提出補丁或修復方案。

### **安全性與系統 (Security & Systems)**

* [computer-forensics](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/computer-forensics) \- 數位取證分析與調查技術。  
* [file-deletion](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/file-deletion) \- 安全檔案刪除與數據淨化方法。  
* [metadata-extraction](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/metadata-extraction) \- 為取證目的提取並分析檔案元數據。  
* [threat-hunting-with-sigma-rules](https://github.com/jthack/threat-hunting-with-sigma-rules-skill) \- 使用 Sigma 檢測規則來追蹤威脅並分析安全事件。

### ---

**透過 Composio 進行應用程式自動化**

透過 [Rube MCP (Composio)](https://composio.dev) 為 78 個 SaaS 應用程式提供預建的工作流技能。每個技能都包含工具序列、參數指導、已知陷阱與快速參考表——全部使用從 Composio API 發現的真實工具標識 (slugs)。

**(此處省略部分詳細應用程式列表，僅列出主要類別：CRM、專案管理、溝通、電子郵件、開發、存儲、試算表、日曆、社交媒體、行銷、支援、電子商務、設計、分析、人力資源、自動化平台、會議。)**

## ---

**入門指南**

### **在 Claude.ai 中使用技能**

1. 點擊對話介面中的技能圖示 (🧩)。  
2. 從市場添加技能或上傳自定義技能。  
3. Claude 會根據你的任務自動啟用相關技能。

### **在 Claude Code 中使用技能**

1. 將技能放置在 \~/.config/claude-code/skills/ 目錄下：  
   Bash  
   mkdir \-p \~/.config/claude-code/skills/  
   cp \-r skill-name \~/.config/claude-code/skills/

2. 驗證技能元數據：  
   Bash  
   head \~/.config/claude-code/skills/skill-name/SKILL.md

3. 啟動 Claude Code：  
   Bash  
   claude

4. 技能會自動加載並在相關時啟用。

### **透過 API 使用技能**

使用 Claude Skills API 以程式化的方式加載與管理技能：

Python

import anthropic

client \= anthropic.Anthropic(api\_key="your-api-key")

response \= client.messages.create(  
    model="claude-3-5-sonnet-20241022",  
    skills=\["skill-id-here"\],  
    messages=\[{"role": "user", "content": "你的提示語"}\]  
)

詳情請參閱 [Skills API 文件](https://docs.claude.com/en/api/skills-guide)。

## ---

**建立技能**

### **技能結構**

每個技能都是一個包含 SKILL.md 檔案（帶有 YAML 前置內容）的資料夾：

skill-name/  
├── SKILL.md          \# 必要：技能指令與元數據  
├── scripts/          \# 選填：輔助腳本  
├── templates/        \# 選填：文件模板  
└── resources/        \# 選填：參考檔案

### **基礎技能模板**

Markdown

\---  
name: my-skill-name  
description: 明確描述此技能的功能以及何時使用它。  
\---

\# 技能名稱

技能用途與能力的詳細說明。

\#\# 何時使用此技能

\- 用例 1  
\- 用例 2

\#\# 指令

\[關於 Claude 如何執行此技能的詳細指令\]

\#\# 範例

\[展示技能運作的實際範例\]

### **技能最佳實踐**

* 專注於特定的、可重複的任務。  
* 包含清晰的範例與邊緣案例。  
* 為 Claude 編寫指令，而非終端用戶。  
* 在 Claude.ai、Claude Code 與 API 之間進行測試。  
* 記錄先決條件與依賴項。  
* 包含錯誤處理指導。

## ---

**參與貢獻**

我們歡迎貢獻！請閱讀我們的 [貢獻指南](https://www.google.com/search?q=CONTRIBUTING.md) 以獲取詳情。

## ---

**相關資源與社群**

* **官方文件**：包含概述、用戶指南、建立指南等。  
* **社群資源**：Anthropic 官方儲存庫、Claude 社群論壇。  
* **加入 Discord**：與其他建立 Claude 技能的開發者交流。

## ---

**授權條款**

本儲存庫採用 Apache License 2.0 授權。

---

**注意**：Claude 技能可在 Claude.ai、Claude Code 和 Claude API 中通用。一旦建立技能，它便可以在各平台間移植，讓你隨處使用 Claude 時都能保持工作流的一致性。

Would you like me to translate any specific skill's sub-documentation or help you draft a new skill based on the template above?