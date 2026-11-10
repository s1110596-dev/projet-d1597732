[github_vibe_coding_prompt (1).md](https://github.com/user-attachments/files/34639845/github_vibe_coding_prompt.1.md)
# 🌿 《文市相逢》｜ 臺中舊城動靜雙核 Citywalk 專題影展
> **行銷二甲 ｜ 甲七組 期中專題企劃**  
> 「以腳步為序，讀一座城。」—— 串聯臺中文學館的靜謐老樹與第五市場的庶民煙火。

---

## 📖 1. 專案簡介 (Project Overview)

《文市相逢》是一份針對 18–28 歲 Z 世代漫遊者與影像創作者打造的 **Citywalk 複合式體驗路線**。專案以一街之隔的「臺中文學館」（靜 ｜ 日式歷史官舍與老樹展覽）與「第五市場」（動 ｜ 百年庶民美食與市井煙火）為核心，透過影片、網頁與文字，傳遞文化底蘊與生活溫度並存的臺中舊城魅力。

---

## 🎨 2. Vibe 視覺與設計語彙 (Design Tokens & Vibe)

本專頁採用**日式 Wabi-sabi 和紙美學**與**雜誌風 (Editorial & Paper Texture Style)** 排版，完全擺脫傳統科技黑或冷調 AI 感：

| 設計元素 | Token / 代碼 | 說明與意象 |
| :--- | :--- | :--- |
| **主背景 (Primary BG)** | `#F9F6F0` | 和紙暖白 (Paper Warm White)，溫潤質感 |
| **卡片背景 (Card BG)** | `#F0ECE1` | 質感柔灰 (Warm Gray)，溫和分層 |
| **苔綠主色 (Brand Moss)** | `#2D3A2F` | 老樹與日式宿舍庭園沉穩氛圍 |
| **赤陶亮點 (Terracotta)** | `#C85A32` | 市場熱氣、庶民小吃與溫暖人情味 |
| **暖墨黑文字 (Warm Ink)**| `#332E2B` | 傳統活字印刷墨跡，閱讀不刺眼 |
| **主字體 (Typography)** | `Noto Serif TC` | 明體/宋體，展現古典文學人文感 |
| **副字體 (Sans-Serif)** | `Inter` | 簡潔現代，適合 Meta 資訊與按鈕 |

---

## 🤖 3. Vibe Coding AI Prompt 系統 (GitHub 專用)

若要使用 AI（ChatGPT / Claude / GitHub Copilot）持續擴充或維護本網頁，請直接複製以下 **System & Master Prompt** 進行開發：

```text
======================================================================
【文市相逢 專案專用 Vibe Coding System Prompt】
======================================================================
[角色定位]
你是一位精通「日式人文雜誌風格」與「Z 世代觀光企劃」的高級前端工程師與視覺設計師。

[設計語言規範 (Design System)]
1. 視覺風格：溫潤和紙風 (Paper Warm Texture)，嚴禁黑色科技感或 AI 質感。
2. 色彩代碼：
   - Primary BG: #F9F6F0 (和紙暖白)
   - Secondary Card: #F0ECE1 (柔灰)
   - Main Brand: #2D3A2F (苔綠)
   - Highlight: #C85A32 (赤陶紅)
   - Text Ink: #332E2B / #787069
3. 排版細節：
   - 大標題與次標題統一使用 serif (Noto Serif TC)。
   - 支援 .writing-vertical 直書文字樣式（用在文化標籤與視覺裝飾）。
   - 按鈕採用圓角 pill (rounded-full) 配合微陰影。

[技術要求]
1. HTML5 語意化標籤 + Tailwind CSS + style.css 獨立檔。
2. 完整 RWD 響應式斷點 (xs:475px, sm:640px, md:768px, lg:1024px)。
3. 嚴謹 SEO 結構化標籤 (Open Graph、Twitter Cards、Schema.org TouristTrip JSON-LD)。
4. 所有景點地圖連結必須包含精確 Google Maps Place ID。
======================================================================
```

---

## 💡 4. 開發 Prompt 範例 (Examples for Prompts)

### 🔹 範例 A：新增「第五市場美食地圖小吃卡片」
> **Prompt**:  
> 「請基於目前的 `#F9F6F0` 和紙風格與 `#2D3A2F` 苔綠色調，在『動靜雙核』區塊下方新增一個三欄式（RWD Responsive Grid）的美食推薦區塊。收錄『太空紅茶冰』、『正老牌麵線羹』與『阿彬爌肉飯』。每張卡片需包含餐點照片、價格區間、地圖連結，並保持圓角與柔和邊框。」

### 🔹 範例 B：更新影片預告與視覺轉場腳本
> **Prompt**:  
> 「請更新『專題故事與影片預告』區塊，以內嵌 YouTube 播放器呈現（Video ID: 6Llx4NClJe8），並強調『湯匙鏡面視覺轉場』與『底片沖洗期待感』兩大創意亮點，保持內文為 12px~14px 舒適字級。」

---

## 📁 5. 專案檔案結構 (Project Tree)

```
taichung-citywalk/
├── index.html          # 專題主要網頁 (含語意化 HTML, SEO 標籤, RWD grid 結構)
├── style.css           # 獨立 CSS 樣式表 (包含 CSS 變數, Reset, Custom Scrollbar, Vertical Text)
├── README_PROMPT.md    # GitHub 專案說明與 Vibe Coding 指南
└── assets/             # 專案靜態資源 (影像與視覺素材)
```

---

## 🚀 6. GitHub 開發與作業提交指南

### 提交至 GitHub 步驟：
```bash
# 1. 初始化 Git 儲存庫
git init

# 2. 加入所有檔案
git add index.html style.css README_PROMPT.md

# 3. 建立首次提交
git commit -m "feat: 完成文市相逢專題網頁與 RWD/SEO/SWOT 企劃升級"

# 4. 推送至 GitHub 遠端儲存庫
git branch -M main
git remote add origin https://github.com/your-username/taichung-citywalk.kiosk.git
git push -u origin main
```

---
© 2026 行銷二甲 甲七組 ｜ 臺中舊城 Citywalk 影展企劃專案
