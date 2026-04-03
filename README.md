# XiaoRuo 個人品牌網站

## 📋 項目描述

這是一個專業的個人品牌靜態網站，展示開發者 XiaoRuo 的作品、服務和 Explan 理財應用。

## 🎨 設計特點

- **色彩方案：** 水藍 / 藍色系現代設計
- **響應式設計：** 完美適配桌面、平板、手機設備
- **現代化界面：** 簡潔現代的 UI/UX 設計
- **性能優化：** 輕量級靜態網站，快速加載

## 📁 項目結構

```
Website/
├── index.html              # 首頁
├── css/
│   └── style.css          # 全局樣式表
├── js/
│   └── script.js          # 交互功能 JavaScript
└── pages/
    ├── explan.html        # Explan APP 詳細介紹頁
    ├── terms.html         # 服務條款
    └── privacy.html       # 隱私政策
```

## 🚀 使用方法

### 1. 本地開發

最簡單的方法是使用 VS Code 的 Live Server 擴展：

1. 安装 VS Code Live Server 擴展
2. 在 `index.html` 上右擊，選擇「Open with Live Server」
3. 網站將自動在 `http://localhost:5500` 打開

或者使用其他本地服務器：

```bash
# 使用 Python 3
python -m http.server 8000

# 或使用 Node.js 的 http-server
npx http-server
```

然後訪問 `http://localhost:8000`

### 2. 部署到網絡

#### 選項 A：使用 GitHub Pages（免費）

1. 在 GitHub 上創建新倉庫 `xiaoruo.github.io`
2. 將項目推送到 main 分支：
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/xiaoruo.github.io.git
git push -u origin main
```
3. 網站自動部署在 `https://yourusername.github.io`

#### 選項 B：使用 Netlify（免費）

1. 訪問 [netlify.com](https://www.netlify.com)
2. 連接你的 GitHub 帳戶
3. 選擇此倉庫
4. 點擊「Deploy」
5. 獲得自動分配的 URL 或連接自定義域名

#### 選項 C：傳統網絡主機

1. 從虛擬主機提供商租賃主機
2. 透過 FTP/SFTP 上傳所有文件到 public_html 目錄
3. 配置自定義域名（如果需要）

#### 選項 D：使用 Vercel（免費）

1. 訪問 [vercel.com](https://www.vercel.com)
2. 使用 GitHub 帳戶登錄
3. 選擇此項目導入
4. 自動部署

## 🎯 頁面結構

### 首頁 (index.html)
- **Hero Section：** 吸引人的主視覺和介紹
- **About Section：** XiaoRuo 的個人介紹和專長
- **Projects Section：** 展示 Explan 和其他作品
- **Footer：** 頁腳信息和相關鏈接

### Explan 頁面 (pages/explan.html)
- 詳細的 APP 功能介紹
- 核心特點展示
- 與傳統應用的對比
- 下載按鈕（可配置應用商店鏈接）
- 常見問題解答 (FAQ)

### 規範頁面
- **服務條款 (terms.html)：** 完整的使用條款
- **隱私政策 (privacy.html)：** 隱私保護政策

## 🔧 技術堆棧

- **HTML5：** 語義化標記
- **CSS3：** 現代樣式和響應式設計
- **JavaScript：** 交互功能和導航控制
- **靜態生成：** 無需後端服務器

## 📝 自定義指南

### 修改顏色方案

編輯 `css/style.css` 中的 CSS 變量：

```css
:root {
  --primary-blue: #0066cc;      /* 主藍色 */
  --light-blue: #00a8ff;        /* 淺藍色 */
  --sky-blue: #00d4ff;          /* 天空藍 */
  --dark-blue: #003d7a;         /* 深藍色 */
  /* ... 其他顏色 */
}
```

### 修改內容

1. 編輯 `index.html` 中的文字內容
2. 修改 Hero Section、About Section 等
3. 添加新的項目卡片到 Projects Section

### 添加新頁面

1. 在 `pages/` 目錄中創建新的 `.html` 文件
2. 複製 header 和 footer 結構
3. 在導航菜單中添加鏈接

## 📱 響應式設計斷點

- **桌面：** 1200px 以上
- **平板：** 768px - 1199px
- **手機：** 480px - 767px
- **小手機：** 480px 以下

## ✨ 功能特點

- ✅ 響應式導航菜單
- ✅ 平滑滾動
- ✅ 懸停動畫效果
- ✅ 移動設備優化
- ✅ 最小化依賴（純 HTML/CSS/JS）
- ✅ 快速加載
- ✅ SEO 友好的標記

## 🔐 安全和隱私

- 完全靜態 - 無後端服務器
- 無數據收集跟蹤（除外：使用分析選項）
- 符合 GDPR 和隱私最佳實踐

## 📊 性能優化

- 最小化文件大小
- CSS 和 JavaScript 內聯簡化
- 無外部依賴
- 快速首次內容繪製 (FCP)

## 🐛 故障排除

### 網站不顯示
- 確保所有文件都在正確的相對路徑中
- 檢查瀏覽器控制台是否有錯誤消息
- 清製瀏覽器緩存

### 樣式不應用
- 確保 `style.css` 路徑正確
- 檢查 CSS 文件是否已損壞
- 驗證 CSS 語法

### JavaScript 不工作
- 確保 `script.js` 路徑正確
- 檢查瀏覽器控制台错误
- 驗證 JavaScript 語法

## 📈 未來改進

- [ ] 添加更多項目案例
- [ ] 實現暗模式主題
- [ ] 添加聯繫表單（需要後端）
- [ ] 集成博客功能
- [ ] 多語言支持

## 📧 聯繫方式

開發者：XiaoRuo  
透過應用內反饋或網站聯繫我

## 📄 許可證

© 2026 XiaoRuo. 版權所有。

## 🙏 致謝

感謝所有支持這個項目的人們！
