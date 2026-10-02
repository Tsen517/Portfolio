# My Portfolio Showcase

使用原生 HTML、CSS、JavaScript 手工打造的響應式個人作品集網站，整理我的學習歷程、專案與技能。

🔗 Live：https://tsen517.github.io/Portfolio/

## 頁面區塊

| 區塊 | 內容 |
|---|---|
| Home | 自我介紹、學習數據、社群連結 |
| About | 背景與學習態度、What Drives Me 卡片 |
| Projects | 專案卡片（圖片、說明、技術標籤、連結） |
| Skills | 技能卡片，品牌色圖示表示已具備，灰色表示學習中 |
| Course | 大學歷程垂直時間軸（左時間、右卡片） |
| Contact | 聯絡方式與社群連結 |

## 使用技術

- **HTML5**：語意化標籤（`section`、`article`、`time`、`ol`）
- **CSS3**：Grid、Flexbox、CSS 變數、`aspect-ratio`、`transition`、Media Query（RWD）
- **JavaScript（原生）**：導覽列目前區塊高亮
- **圖示**：Font Awesome 6.5、Devicon
- **版本控管與部署**：Git、GitHub、GitHub Pages
- **開發工具**：VS Code、Live Server、Chrome DevTools

## 我的貢獻

- 規劃頁面結構與資訊架構，撰寫全部內容文字
- 以 CSS Grid 完成各區塊響應式版面（桌機、平板、手機）
- 實作垂直時間軸（Course）與技能卡片的「已具備／學習中」圖示狀態
- 設計卡片 hover 互動與導覽列樣式
- 準備專案截圖與操作示範素材
- 使用 Git 管理版本，並部署至 GitHub Pages

## 開發進度

- [x] 各區塊靜態版面
- [x] hover 互動效果
- [ ] 捲動浮現動畫
- [ ] 首頁載入動畫
- [ ] 手機版導覽選單
- [ ] 專案 Demo 影片

## 開發方式與參考

- 版面設計參考開源作品集 [Amine Hamzaoui](https://github.com/Saboo24)，內容文字與專案素材為自行準備。
- 使用 AI 工具作為學習與除錯的輔助：由我決定頁面結構與內容，AI 協助提供程式碼草稿與語法建議。
- 採用前會逐段閱讀、實際執行並以 DevTools 驗證，理解原理後再整合，並將踩坑經驗整理成筆記。

## 本機執行

```bash
git clone https://github.com/Tsen517/Portfolio.git
cd Portfolio
# 用 VS Code 的 Live Server 開啟 index.html
```