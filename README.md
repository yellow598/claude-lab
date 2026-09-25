# TEST Studio｜平面設計接案作品集

TEST的平面設計師個人接案網站，單頁式 Landing Page，展示品牌識別、包裝設計與社群視覺作品。

## 網站功能

- **英雄區塊**：主標題、副標題、接案狀態標籤、成果數據，以及「與我聯繫」「觀看作品」兩個 CTA 按鈕
- **精選作品**：三張作品卡片，每張包含圖示、專案類別、專案名稱與設計理念說明，滑鼠移入有浮起效果
- **聯繫區塊**：邀請合作的 CTA 與寄信按鈕
- **頁尾**：版權資訊與社群連結
- **導覽列**：固定於頂部的毛玻璃導覽列，點擊可平滑捲動至各區塊
- **淡入動畫**：頁面載入時各區塊依序淡入上浮（系統開啟「減少動態效果」時自動停用）
- **RWD 響應式設計**
  - 900px 以下：作品卡片改為單欄垂直排列
  - 600px 以下：大標題縮小為桌面版的 75%、按鈕滿版垂直排列
  - 所有按鈕與連結最小高度 44px，觸控友善
  - 375px 寬度下無任何元素超出螢幕

## 使用技術

- **HTML5**：語意化標籤（`header`、`main`、`section`、`article`、`footer`）
- **CSS3**：CSS 變數、Flexbox、Grid、漸層背景、`backdrop-filter`、`@keyframes` 動畫、Media Queries
- **Google Fonts**：Inter（英文）、Noto Sans TC（中文）
- **圖示**：內嵌 SVG，無需額外圖檔

不使用任何框架或 JavaScript，所有樣式都寫在 `index.html` 內。

## 如何開啟

不需要安裝任何套件或伺服器：

1. 下載或 clone 這個專案
   ```bash
   git clone XXXX
   ```
2. 進入資料夾，直接用瀏覽器（Chrome、Edge、Safari、Firefox）開啟 `index.html`
   - 雙擊 `index.html`，或
   - 把檔案拖曳到瀏覽器視窗中

> 需要網路連線才能載入 Google Fonts 字型；離線時會自動改用系統字型。

### 預覽手機版

在瀏覽器按 `F12` 開啟開發者工具，點選「切換裝置工具列」（`Ctrl + Shift + M`），選擇 iPhone SE 或自訂寬度 375px 即可預覽。

## 上線前待替換

- 聯繫按鈕的 Email（目前為 `hello@example.com`）
- 頁尾 Instagram / Behance / Dribbble 連結
- 作品卡片與數據為示意內容，請換成真實專案

## 檔案結構

```
claude-lab/
├── index.html   # 網站主頁（HTML + CSS）
├── note.txt
└── README.md
```

---

© 2026 TEST studio
